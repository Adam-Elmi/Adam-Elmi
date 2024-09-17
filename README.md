## Hi there 👋 I'm Adam
```js
function getAge(birthYear) {
    const age = (new Date().getFullYear() - birthYear);
    return age;
};

function me() {
    return {
        name: "Adam Elmi",
        age: getAge(2000),
        email: "adamcade123@gmail.com",
        phone: "+252634709061",
        address: "Hargeisa,Somaliland",
        website: "Coming Soon",
        github: "https://github.com/Adam-Elmi",
        favQuote: "The only way to do great work is to love what you do. - Steve Jobs",
        favLanguage: "JavaScript",
        hobbies: ["coding and programming", "reading", "watching anime", "walking alone", "learning new things about js"],
    };
};

console.log(me());
```

