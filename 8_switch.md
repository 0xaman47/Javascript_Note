___
### Switch in JS 
___
___
#### Switch :
* The JavaScript switch statement is used in decision making.
* The switch statement is used to perform different actions based on different conditions.
* Use the switch statement to select one of many code blocks to be executed.
* The switch statement evaluates an expression and executes the corresponding body that matches the expression's result.

```s
switch(variable/expression) {
    case value1:  
        // body of case 1
        break;

    case value2:  
        // body of case 2
        break;

    case valueN:
        // body of case N
        break;

    default:
        // body of default
}
```
EX...
```javascript
// program using switch statement
let a = 2;

switch (a) {

    case 1:
        a = 'one';
        break;
    case 2:
        a = 'two';
        break;
    default:
        a = 'not found';
        break;
}
console.log(`The value is ${a}`);
```