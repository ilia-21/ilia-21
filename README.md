<!---
interface CollegeStudent {
  name: string;
  nickname: string;
  age: number;
  education: {
    major: string;
    expectedGraduation: string;
    relevantCoursework: string[];
  };
  currentlyLearning: string[];
  skills: string[];
  OS: string;
  hobbies: string[];
}
--->

```typescript
const user: CollegeStudent = {
  name: "Ilya",
  nickname: "ilia21",
  age: 18,
  education: {
    major: "Computer Science",
    expectedGraduation: "June 2026",
    relevantCoursework: ["Mobile Development", "Database managment", "Operating Systems", "Algorithms"],
  },
  currentlyLearning: ["React"],
  skills: ["NodeJS", "HTML/CSS", "Java", "Typescript"],
  OS: "Arch linux",
  hobbies: ["Coding", "Gaming", "Biking"],
};
```
