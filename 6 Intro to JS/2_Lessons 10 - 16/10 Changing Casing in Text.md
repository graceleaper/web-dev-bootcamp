# Changing Casing in Text

- `toUpperCase()` and `toLowerCase()` methods

```
let name = "Grace";
name = name.toUpperCase();
console.log(name);
```

```
let name = "Grace";
name = name.toLowerCase();
console.log(lowerCaseName);
```
- Will be handy if person who typed their name didn't capitalize the first letter in their name when prompted to type their name. Also handy if you want to capitalize all letters in the name
- Challenge: capitalize just the first letter of a name. And create an alert using this name and write a message. Use .slice() and the .toUpperCase() methods in solution
```
let name = prompt("What is your name?");

let upperCaseLetter = name.slice(0, 1).toUpperCase();

let restOfName = name.slice(1);

alert("Welcome to Amazon, " + upperCaseLetter + restOfName + "!");
```
- Bonus challenge: what if user types in capitalized letters _within_ their name? Then add the following:

```
let restOfName = name.slice(1).toLowerCase();
```