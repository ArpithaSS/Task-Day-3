For the given JSON iterate over all for loops (for, for in, for of, forEach)

var obj={
    name:"Alice",
    age:23
};
var size= Object.keys(obj).length;
var ele=Object.values(obj);
console.log(size);
//for loop- to print value
for(var i=0;i<size;i++)
{
    console.log(ele[i]);
}
//for in loop-to print obj key and value
for(var i in obj){
console.log(i,obj[i]);
}
//for of loop- to print value
for(let i of ele){
    console.log(i);
}
//for each loop- to print obj key and value
Object.entries(obj).forEach(([key, value]) => {
  console.log(key, value) 
})
---------------------------------------------------------------
Create your own resume data in JSON format

var resume={
    Name: "Arpitha Naik",
    ContactNo: 8310318146,
MailID: "arpithanaik17@gmail.com",
Place: "Bengaluru",
ProfessionalSnapshot:['Around 4 years of Experience as Application Support Engineer in DXC Technology','Good Knowledge on Software development life cycle (SDLC)',	'Expertise in Application Maintenance and Production Support.','Excellent Analytical and problem-solving skills.','Expertise in handling multiple tasks simultaneously with equal attention','Worked on Incident management, Windows patching activities from application end.'
],
TechnicalSkills:['React','Javascript','HTML','CSS','Web API'],
WorkingExperience: '5 years',
Client: 'American Airlines',
Responsibilities: ['Technical Support','Issue analysis'],
Strengths: ['Adaptive','Quick learner']
};
--------------------------------------------------------------------
Read about the difference between window, screen and document in javascript
Window is the main JavaScript object root, aka the global object in a browser, and it can also be treated as the root of the document object model. You can access it as window.

window.screen or just screen is a small information object about physical screen dimensions.

window.document or just document is the main object of the potentially visible (or better yet: rendered) document object model/DOM.

Since window is the global object, you can reference any properties of it with just the property name - so you do not have to write down window. - it will be figured out by the runtime
