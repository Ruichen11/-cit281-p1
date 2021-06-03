# CIT281 Project-1

Purpose of this project: 
- To gain experience with operating system command line interface 
- Gain experience working with VSCode
- Gain experience writing and exxecuting non-web server Node.js JavaScript code 

### Project Code:
- Output to the console the day of the week of the current day. The day of the week must be the full name for the day.
```
function days_of_Week() {
    var d = new Date();
    var days = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
    return(days[d.getDay()]);
}
console.log(days_of_Week)
```

- Output to the console a string of random length between 5-25 characters in length, that consists of all random lowercase letter from the english alphabet. 
- Returns a random number between min (inclusive) and max (exclusive)
``` 
function getRandomInteger(min, max) {
    return Math.floor(Math.random() * (max - min) + min);
}
const alphabet = "abcdefghijklmnopqrstuvwxyz".split("");
let result = "";
let lengthOfOutputString = getRandomInteger(5, 26);
for (let i = 0; i < lengthOfOutputString; i++) {
    result += alphabet[getRandomInteger(0,alphabet.length)];
}
console.log(result);
```

### What I learned from this project:
- Learned how to use the CLI of my operating system to create folders 
- Created and executed JS files using Node.js and VSCode terminal


[Source code](https://ruichen11.github.io/Ruichen11.CIT-Minor/)
