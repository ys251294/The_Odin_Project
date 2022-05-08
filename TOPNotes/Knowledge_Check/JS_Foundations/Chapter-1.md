# JAVASCRIPT Foundations Chapter - 1

### Que: Name the three ways to declare a variable?

**Ans:** let, const and var (! not recommended).

### Que: Which of the three variable declarations should you avoid and why?

**Ans:** var

### Que: What rules should you follow when naming variables?

**Ans:**
- Use [a-z], [A-Z], [1-9], $, and _.
- First Character should not be numeric.
- Write human readable name.
- use cameCase.  

### Que: What should you look out for when using the + operator with numbers and strings?

**Ans:** `+` operator work as addition and concatenation operator, I should lookout for that and not confuse them with each other.  
PS: JS work on left to right in most cases.

### Que: How does the % operator work?
**Ans:** It provide remainder of two operands.
eg. - 10%3 return 1

### Que: Explain the difference between == and ===.
**Ans:**
|==|===|
|:---|:---|
|loose equal operator|strict equal operator|
|check if values of operands are equal|check if values as well as type of operands are equal|

### Que: When would you receive a NaN result?
**Ans:** When string or variable can not be coerced into number.

### Que: How do you increment and decrement a number?
**Ans:** 
- using prefix or postfix operator.
- using addition and subtraction operator.
- using addition assignment (+=) or subtraction assignment operator (-=).

### Que: Explain the difference between prefixing and post-fixing increment/decrement operators.
**Ans:** 
* Prefixing increment/decrement operator : update the variable then return the value of variable.
* Postfixing increment/decrement operator : update the variable then return the old value of variable.

### Que: What is operator precedence and how is it handled in JS?
**Ans:** Operator precedence decide sequence of operator calculation in an expression.

### Que: How do you access developer tools and the console?
**Ans:** 
* Right click->Inspect->console.
* F12.
### Que: How do you log information to the console?
**Ans:** `console.log();`

### Que: What does unary plus operator do to string representations of integers?
**Ans:** it convert them into numbers.