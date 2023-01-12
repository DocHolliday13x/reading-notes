# Class 7: Programming w/JavaScript

## Resources

* [MDN Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)
* [JavaScript Functions](https://www.w3schools.com/js/js_functions.asp)
* [JavaScript Operators](https://www.w3schools.com/js/js_operators.asp)
* [MDN Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
* [MDN Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

## Some Notes

**Control Flow**

* Control Flow = the order in which the cpu executes statements in a script.
  * Code is run in order from first line to last line unless there are structures that change control flow, such as _conditionals_ and _loops_.
* A typical script in JS or PHP includes many control structures, including _conditionals_, _loops_ and _functions_. Parts of a script may also be set to execute when _events_ occur.

**JavaScript Functions**

* A JS _function_ is a block of code designed to perform a particular task.
* _Functions_ are executed when something "calls it"
  * // Function to compute the product of p1 and p2
function myFunction(p1, p2) {
  return p1 * p2;
}
* For a procedure to qualify as a _funtion_, it should take some input and _return_ an output where there is some obvious relationship between the input and output.

**JavaScript Function Syntax**

* JS _functions_ are defined with the _function_ keyword, followed by a name, followed by parentheses ().
* _Function_ names follow same rules as _variables_ (contains letters, digits, underscores, and dollar signs).
* The code to be executed by the _function_ is placed inside curly brackets {}.
* function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

**Function Return**

* When JS reaches a _return_ statement, the _function_ will stop executing.
* If the _function_ was called from a statement, JS will _return_ to execute the code after the invoking statement.
* _Functions_ often compute a _return_ value. The _return_ value is "returned" back to the "caller".
* let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
* With _functions_ you can define the code once and use it many times.
  * You can use the same code many times with different _arguments_ to produce different results.
    * function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);
* The () Operator invokes the _function_
  * function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius;
* _Functions_ can be use as _Variable_ values
  * let x = toCelsius(77);
let text = "The temperature is " + x + " Celsius";

**Local _Variables_**

* _Variables_ declared within a JS _function_ become LOCAL to the _function_.
  * Local _variables_ can only be accessed from within the _function_.
  * // code here can NOT use carName

function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}

// code here can NOT use carName

**JavaScript Operators**

* The assignment operator (=) assigns a value to a _variable_.
  * let x = 10;
* The addition operator (+) adds numbers.
  * let x = 5;
let y = 2;
let z = x + y;
* The multiplication operator (*) multiplies numbers.
  * let x = 5;
let y = 2;
let z = x * y;

**Types of JS Operators**
* 1. Arithmetic Operators
  * Additon = +
  * Subtraction = -
  * Multiplication = *
  * Exponentiation = **
  * Division = /
  * Modulus (Division Reminder) = %
  * Increment = ++
  * Decrement = --
* 2. Assignment Operators
  * +=  example (x += y)=(x= x + y)
  * -=  example (x -= y)=(x= x - y)
  * *=  example (x *= y)=(x= x * y)
  * /*  example (x /= y)=(x= x / y)
  * %=  example (x %= y)=(x= x % y)
  * **= example (x **= y)=(x= x ** y)
* 3. Comparison Operators
  * ==   eqaul to
  * ===  equal value and equal type
  * !=   not equal
  * !==  not equal value or not equal type
  * >    greater than
  * <    less than
  * >=   greater than or equal to
  * <=   less than or equal to
  * ?    ternary operator
* 4. Logical Operators
  * &&  logical and
  * ||  logical or
  * !   logical not
* 5. Conditional Operators
* 6. Type Operators
  * typeof       Returns the _type_ of a _variable_
  * instanceof   Returns _true_ if an object is an instance of an object type


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

#### Things I Would Like to Know More About

Maybe in time, I will be able to memorize most of these operators, but as of right now there are soooooo many. I will have to reference the MDN often until I get the hang of these things.


