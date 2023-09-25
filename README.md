# Iliass Farsi (IliFar)

```javascript
const iliassFarsi = {
  name: "Iliass Farsi",
  jobTitle: "Software Developer | Web Developer | Application Developer | System Developer",
  expertise: [
    ".NET",
    "C#",
    "JavaScript",
    "React",
    "React Native",
    "TypeScript",
    "SpecFlow",
    "Express"
  ],
  hobbies: [
    "Spend time with family and friends",
    "Programming",
    "Martial Arts",
    "Football",
    "Music",
    "Tech"
  ],
  catchPhrase: "Forging brilliance through each keystroke, shaping remarkable software with every line of code!",
  get introduction() {
    return `Hi, my name is ${this.name} and I am a ${this.jobTitle}. I have expertise in technologies like ${this.expertise.join(", ")}. When I'm not coding, you can find me ${this.hobbies.map(hobby => `enjoying ${hobby}`).join(", ")}. ${this.catchPhrase}`;
  }
};

console.log(iliassFarsi.introduction);
```

[![trophy](https://github-profile-trophy.vercel.app/?ilifar)](https://github.com/ryo-ma/github-profile-trophy)
