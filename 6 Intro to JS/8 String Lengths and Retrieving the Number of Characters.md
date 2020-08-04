# String Lengths and Retrieving the Number of Characters

## length property

```
let name = "Grace";
console.log(name.length);

// we'll be returned 5
```

- Challenge: Write a Twitter message saying how many characters you have, and how many characters you have left given a sentence
- Note that 2 forward slashes are used to make single-line comments in JavaScript
    - Or use /* */ for multi-line comments

```
// You have written 182 characters. You have -42 characters left

let tweet = prompt("Compose your tweet:");
let tweetCount = tweet.length;
alert("You have written " + tweetCount + "characters. You have " + (140 - tweetCount) + " characters left.");

```
- Can also just have:

```
// You have written 182 characters. You have -42 characters left

let tweet = prompt("Compose your tweet:");
alert("You have written " + tweet.lengths + "characters. You have " + (140 - tweetCount) + " characters left.");

```
- Showed original code snippet, since it's good practice to store values in variables that hold numbers