<!---
interface CollegeStudent {
  nickname: string;
  age: number;
  education: {
    major: string;
    expectedGraduation: string;
  };
  skills: string[];
  OS: string;
  hobbies: string[];
}
--->

```typescript
const user: CollegeStudent = {
  nickname: "Mahonzu",
  age: 19,
  education: {
    major: "Computer Science",
    expectedGraduation: "June 2026"
  },
  skills: ["NodeJS", "HTML/CSS", "Java", "Typescript"],
  OS: "Arch linux",
  hobbies: ["Coding", "Gaming"]
};
```
