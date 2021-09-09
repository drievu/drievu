- // My name
- const myName = '@drievu';

- // My skills
- const mySkills = {
    linuxDistros: ['RHEL8', 'Fedora34'],
    cloudPlatforms: ['AWS'],
    codingLanguages: ['Python', 'JavaScript']
  };
  
- // Other skills
- const myOtherSkills = {
    additionalCodingSkills: ['ReactJS', 'node.js', 'express.js', 'redux']
    interpersonalSkills: ['Team management', 'Troubleshooting', 'Written & oral communication']
  };
  
- // My contact details
- const contactMe = {
    email: 'nvj.7186@gmail.com',
    mobile: '9867101327'
  };

- // My profile
- myInfo = () => {
    console.log(
      `Hi! my name is ${myName} & I am a passionate developer. 
      I am currently learning JavaScript, ${...myOtherSkills.additionalCodingSkils}.
      My list of skills contain ${...mySkills}.
      I believe I am also good in ${...myOtherSkils.interpersonalSkills}.
      You can contact me at ${...contactMe}`
    );
  };
  
  myInfo();
