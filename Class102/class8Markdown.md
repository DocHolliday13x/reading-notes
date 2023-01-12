# Class 8: Operators and Loops

## Resources

* [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
* [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

## Some Notes

### **Assignment Operators**

* Assignment: x = f()
* Addition Assignment: x += f()
* Subtraction Assignment: x -= f()
* Multiplication Assignment: x *= f()
* Division Assignment: x /= f()
* Remainder Assignment: x %= f()
* Exponentiation Assignment: x **= f()
* Left Shift Assignment: x <<= f()
* Right Shift Assignment: x >>= f()
* Unsigned Right Shift Assignment: x >>>= f()
* Bitwise AND Assignment: x &= f()
* Bitwise XOR Assignment: x ^= f()
* Bitwise OR Assignment: x |= f()
* Logical AND Assignment: x &&= f()
* Logical OR Assignment: x ||= f()
* Nullish Coalescing Assignment: x ??= f()

### **Comparison Operators**

* Eqaul: (==)
* Not Eqaul: (!=)
* Strict Equal: (===)
* Strict Not Equal: (!==)
* Greater Than: (>)
* Greater Than or Eqaul: (>=)
* Less Than: (<)
* Less Than or Eqaul: (<=)

### **For Statements**

* A _for_ loop repeats until a specified condition evaluates to false.
  * for ([initialExpression]; [conditionExpression];
    [incrementExpression])
    statement
* While a _for_ loop executes:
  * 1. [initailExpression] (if any) is executed.
  * 2. [conditionExpression] is evaluated. If the value of [conditionExpression] is true, the loop statements execute. Otherwise, the _for_ loop terminates. If the [conditionExpression] is omitted entirely, the condition is assumed to be true.
  * 3. The statement executes. To execute multiple statements, use a _block statement_ ({}) to group those statements.
  * 4. If present, the [incrementExpression] is executed.
  * 5. Control returns to Step 2.

### **While Statements**

* A _while_ statement executes its statement as long as a specified condition evaluates to _true_.
  * while (condition)
      statement
* If the condition becomes _false_, statement within the loop stops executing and control passes to the statement following the loop.
* The condition test occurs before statement in the loop is executed. If the condition returns _true_, statement is executed and the condition is tested again. If the condition returns _false_, execution stops, and control is passed to the statement following _while_.
* To execute multiple statements, use a block statement ({}) to group those statements.

Example:
let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}


#### Practice

function favColor(){
    let userGuess = prompt("What is my favorite color?");
    if (userGuess == "yellow"){
        console.log("That is correct");
    } else {
        console.log("That is wrong");
        favColor();
    }
}
// This _function_ will continue to _loop_ until the correct answer is given.


#### Things I Would Like to Know

I would like to get to a point skillwise where I can tell when it's most efficient to loop with a function, or with an actual loop (whether the loop is a _for_ loop or a _while_ loop).

