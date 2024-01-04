<!-- website = "https://example.com"; -->

```js
import { SoftwareDeveloper } from "@mohammedhassad";

class Bio extends SoftwareDeveloper {
  pronouns = "He" | "Him";
  name = "Mohammed Hassad";
  title = "Full Stack Developer";
  linkedin = "https://linkedin.com/in/mohamedhassad";
}

class Skills extends SoftwareDeveloper {
  languages = ["JavaScript", "TypeScript", "PHP", "Python"];
  databases = ["MongoDB", "MySQL", "MariaDB"];
  frameworks = {
    frontEnd: {
      js: ["React", "Next", "Redux", "Zustand"],
      css: ["Bootstrap", "Tailwind CSS", "Sass", "Material UI", "Chakra UI"],
    },
    backEnd: {
      js: ["Node", "Express"],
      php: ["Symfony"],
    },
  };
  devOps = ["Docker🐳", "Apache", "Git"];
  misc = ["Firebase", "Puppeteer", "Selenium", "REST APIs", "GraphQL", "JWT"];
  architecture = ["MVC", "SPA", "PWA"];
  funFact = "There are two ways to write error-free programs; only the third one works";
}
```

<!-- ```js
export default () => ({
   pronouns: "He" | "Him",
    code: ["Javascript", "Typescript", "Python", "Java", "php"],
    askMeAbout: ["web dev", "tech", "app dev", "photography"],
    technologies: {
        mobileApp: ["Android App"],
        frontEnd: {
            js: ["Vue", "Nuxt"],
            css: ["materialize", "vuetify", "bootstrap"]
        },
        backEnd: {
            js: ["node", "express", "SuiteScript"],
            python: ["flask"]
        },
        devOps: ["AWS", "Docker🐳", "Route53", "Nginx"],
        databases: ["mongo", "MySql", "sqlite"],
        misc: ["Firebase", "Socket.IO", "selenium", "open-cv", "php", "SuiteApp"]
    },
    architecture: ["Serverless Architecture", "Progressive web applications", "Single page applications"],
    currentProject: "I am developing Extension for NetSuite using SuiteScript2.0",
    funFact: "There are two ways to write error-free programs; only the third one works"
});
``` -->
