[![Lorenzo Fratus](assets/header.gif "Lorenzo Fratus")](https://www.lorenzofratus.it/)

# Hi, there! ✌️

## 👨‍💻 Anything you need to know about me...

```javascript
const myself = {
    firstName: 'Lorenzo',
    lastName: 'Fratus',
    country: 'Italy',
    contact: 'info@lorenzofratus.it',
    status: {
        current: 'College student',
        future: 'Software engineer',
    },
    education: () => {
        const expectedGraduation = new Date(2022, 12, 0);
        return Date.now() < expectedGraduation
            ? {
                major: 'Computer Science',
                degree: 'Ingegneria Informatica',
                level: 'Bachelor',
                university: 'Politecnico di Milano'
            }
            : {
                major: 'Computer Science',
                degree: 'Computer Science and Engineering',
                level: 'Master',
                university: 'Politecnico di Milano'
            }
    },
    languages: {
        favorite: 'JavaScript',
        oftenUsed: [
            'Dart',
            'Java',
            'Python',
            'HTML',
            'CSS'
        ],
        occasional: [
            'C++'
            'C'
        ]
    },
    tools: [
        'Flutter',
        'NodeJS',
        'ExpressJS',
        'NuxtJS',
        'MySQL',
        'Wordpress',
        'Adobe suite'
    ]
}
```
