// Personal information
const fullName = "srinivasan";
const age = 22;
const gender = "Male";
const DOB = "08-02-2001";
const occupation = "Bug Developer";

// Contact details
const email = "Srinivasanbr0802@gmail.com";
const phone = "+916383745916";
const address = "Coimbatore, Tamil Nadu,India Country";

// Education details
const education = [
  {
    degree: "Bachelor of Science in Computer Science",
    university: "Bharathiyar university",
    year: 2021
  },
  {
    degree: "High School Diploma",
    school: "Csi Boys Hr sec school",
    year: 2018
  }
];

// Skills
const skills = ["JavaScript", "HTML", "CSS", "Python", "React", "Node.js"];

// Displaying bio data
console.log("Full Name: " + fullName);
console.log("Age: " + age);
console.log("Gender: " + gender);
console.log("DOB: " + DOB);
console.log("Occupation: " + occupation);
console.log("Email: " + email);
console.log("Phone: " + phone);
console.log("Address: " + address);

console.log("Education:");
education.forEach((edu) => {
  console.log("- " + edu.degree + " from " + (edu.university || edu.school) + ", " + edu.year);
});

console.log("Skills: " + skills.join(", "));








