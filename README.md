[![Lorenzo Fratus](assets/header.gif "Lorenzo Fratus")](https://www.lorenzofratus.it/)

# Hi, there! ✌️

## 👨‍💻 Anything you need to know about me...

```javascript
const myself = {
    firstName: "Lorenzo",
    lastName: "Fratus",
    country: "Italy",
    contact: "info@lorenzofratus.it",
    workStatus: [
        {
            role: "Founder",
            company: "Teapot Labs",
        },
        {
            role: "SAP Cloud Application Developer",
            company: "Syscons Futura",
        }
    ],
    education: () => {
        const expectedGraduation = new Date(2023, 05, 04);
        return Date.now() < expectedGraduation
            ? {
                major: "Computer Science",
                degree: "Ingegneria Informatica",
                level: "Bachelor",
                university: "Politecnico di Milano"
            }
            : {
                major: "Computer Science",
                degree: "Computer Science and Engineering",
                level: "Master",
                university: "Politecnico di Milano"
            }
    },
    languages: {
        favorite: "JavaScript",
        oftenUsed: [
            "TypeScript",
            "Python",
            "Dart",
            "Java",
            "HTML",
            "CSS"
        ],
        occasional: [
            "C++",
            "C"
        ]
    },
    frameworks: [
        "React",
        "Flutter",
        "CAP",
        "Vue",
        "Express"
    ],
    tools: [
        "Figma",
        "Adobe Illustrator",
        "Adobe Photoshop"
    ]
}
```
