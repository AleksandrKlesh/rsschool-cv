# Aleksandr Klesh

## Junior Frontend Developer

### Contact information:

-   **Phone:** +84564327746
-   **E-mail:** alex73kl@gmail.com
-   **Telegram:** @MoonFuryyy
-   **Discord:** AlexKl
-   **GitHub:** [AleksandrKlesh](https://github.com/AleksandrKlesh)

### Summary

I am a motivated and ambitious person alsp I appreciate and understand the importance of programming in our everyday live. I am convinced that the more effort you put in it the bigger result you get.

### Skills

-   HTML
-   CSS (SCSS)
-   JavaScrript Basics
-   Git, GitHub
-   Adobe Photoshop, Figma
-   Editors: Sublime, VSCode

### Code Examples

```
const flights =
  '_Delayed_Departure;fao93766109;txl2133758440;11:25+_Arrival;bru0943384722;fao93766109;11:45+_Delayed_Arrival;hel7439299980;fao93766109;12:05+_Departure;fao93766109;lis2323639855;12:30';

const getCode = str => str.slice(0, 3).toUpperCase();

for (const flight of flights.split('+')) {
  const [type, from, to, time] = flight.split(';');

  const output = `${type.startsWith('_Delayed') ? '🔴' : ''} ${type.replaceAll(
    '_',
    ' '
  )} ${getCode(from)} ${getCode(to)} ${time.replace(':', 'h')}`.padStart(35);
  console.log(output);
}
```

### Education (courses)

-   Ulyanovsk Aviation College
    -Computer Science and Information technology
-   Ulyanovsk State University
    -Aircraft construction
-   [CS50 2020](https://www.youtube.com/watch?v=YoXxevp1WRQ&list=PLhQjrBD2T382_R182iC2gNZI9HzWFMC_8&ab_channel=CS50)
-   HTML and CSS Tutorials on the [freeCodeCamp](https://www.freecodecamp.org/)
-   JavaScript Tutorials on the [freeCodeCamp](https://www.freecodecamp.org/)
-   JavaScript Course [Udemi](https://www.udemy.com/course/the-complete-javascript-course/)

### Languages

-   Russian (native)
-   English (C1)
