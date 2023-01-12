# Class 7: Programming w/JavaScript

## Resources

* [MDN Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)
* [JavaScript Functions](https://www.w3schools.com/js/js_functions.asp)
* [JavaScript Operators](https://www.w3schools.com/js/js_operators.asp)
* [MDN Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
* [MDN Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

## Some Notes


#### Replit Practice

// declaring a variable called theName
// assigning it the value of the result of prompting
// "What is your name?"

let favColor = "yellow"
let userGuess = prompt("What is my fav color?");
userGuess = userGuess.toLowerCase();
console.log("Now user guess is: " + userGuess);
//
console.log("User guess is: " + userGuess);
if (userGuess == favColor){
  console.log("You are right.");
} else {
  console.log("You are wrong.");
}
//
let userName = prompt("What is your name?");

if (userName == "ryan") {
  console.log("Hola compa, hear any good chisme on the cartel lately?");
} else {
  console.log("Buenos Dias, Bolivia")
} 
console.log("Welcome to Bolivia " + userName);
//




