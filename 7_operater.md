### Operators : 
* in Javascript operators perform mathematical function.
* operators likes a symbol that are use to perform mathematical operation.
  ```s 
  ex.. var sum = 10 + 20;
  ```

##### There are some types of operator in javascript :
- Assignment Operators
- Arithmetic Operators
- Comparison Operators
- Logical Operators
- Bitwise Operators
- Ternary Operators

##### 1. Assignment Operators : 
* In javascript Assignment Operators provides assignment operators to assign values to variables with less key strokes.

|Operators|Name|Example|
|-|-|-|
|`=`|Assignment operators|`a = 7;`|
|`+=`|Addition assignment|`a += 5; // a = a + 5`|
|`-=`|Subtraction assignment|`a -= 5; // a = a - 5`|
|`*=`|Multiplication assignment|`a *= 5; // a = a * 5`|
|`/=`|Division assignment|`a /= 5; // a = a / 5`|
|`%=`|Remainder assignment|`a %= 5; // a = a % 5`|

##### 2. Arithmetic Operators :
* Athematic Operators perform athematic operation.
  ```s
  ex.. number = 3 + 5; // 8
  ```
  |Operators|Name|Example|
  |-|-|-|
  |`+`|Addition|`x + y`|
  |`-`|Subtraction|`x - y`|
  |`*`|Multiplication|`x * y`|
  |`/`|Division|`x / y`|
  |`%`|Reminder|`x % y`|
  |`++`|Increment|`++x` `x++`|
  |`--`|Decrement|`--x` `x--`|
  |`**`|Exponentiation|`x ** y`|

  
```s
  let x = 5;
  let y = 3;

// addition
console.log('x + y = ', x + y);  // 8

// subtraction
console.log('x - y = ', x - y);  // 2

// multiplication
console.log('x * y = ', x * y);  // 15

// division
console.log('x / y = ', x / y);  // 1.6666666666666667

// remainder
console.log('x % y = ', x % y);   // 2

// increment
console.log('++x = ', ++x); // x is now 6
console.log('x++ = ', x++); // prints 6 and then increased to 7
console.log('x = ', x);     // 7

// decrement
console.log('--x = ', --x); // x is now 6
console.log('x-- = ', x--); // prints 6 and then decreased to 5
console.log('x = ', x);     // 5

//exponentiation
console.log('x ** y =', x ** y);
```

##### 3. Comparison Operators :
* Comparison Operators use two compare two value and return a boolean values, either `true` or `false`.
```html
const a = 3, b = 2;
console.log(a > b); // True
```

|Operators|Name|Example|
|-|-|-|
|`==`|Equal to|`x == y`|
|`!=`|Not Equal to|`x != y`|
|`===`|Strict equal to|`x === y`|
|`!==`|Not strict equal to|`x !== y`|
|`>`|Greater than|`x > y`|
|`>=`|Greater than equal to|`x >= y`|
|`<`|Less than|`x < y`|
|`<=`|Less than Equal to|`x <= y`|

```s
  // equal operator
console.log(2 == 2); // true
console.log(2 == '2'); // true

// not equal operator
console.log(3 != 2); // true
console.log('hello' != 'Hello'); // true

// strict equal operator
console.log(2 === 2); // true
console.log(2 === '2'); // false

// strict not equal operator
console.log(2 !== '2'); // true
console.log(2 !== 2); // false
```

##### 4. Logical Operators :
* logical operators perform logical operation and return boolean value, either `true` or `false`.
  
Ex...
```s
 const x = 5, y = 3;
 (x < 6) && (y < 5); // true
``` 
|Operators|Name|Example|
|-|-|-|
|`&&`|Logical AND|`x && y`|
|`||`|Logical OR|`x || y`|
|`!`|Logical NOT|`!x`|

```s
  // logical AND
console.log(true && true); // true
console.log(true && false); // false

// logical OR
console.log(true || false); // true

// logical NOT
console.log(!true); // false
```

##### 5. Bitwise Operators :
* Bitwise operators perform operations on binary representations of numbers.

|Operators|Name|Example|
|-|-|-|
|`&`|Bitwise AND|`x & y`|
|`|`|Bitwise OR|`x | y`|
|`^`|Bitwise XOR|`x ^ y`|
|`~`|Bitwise NOT|`~x`|
|`<<`|Bitwise Left Shift|`x << y`|
|`>>`|Bitwise Right Shift|`x >> y`|
|`>>>`|Bitwise Right Shift with Zero|`x >>> y`|  

Ex...
```s
let a = 12; 
let  b = 25; 

// bitwise AND operator example
result = a & b; 
console.log(result); // 8 

// bitwise OR operator example
result = a | b; 
console.log(result); // 29

// bitwise XOR operator example
result = a ^ b; 
console.log(result); // 21

// bitwise NOT operator example
result = ~b;
console.log(result); // -13
```
```s
let a = 8;
let b = 1;

//bitwise left shift
result = a << b;
// 1 ( 00000000000000000000000000010000 )
console.log(result);

// bitwise right shift
// 11111111111111111111111111111101
let c = -3;

result = a >> b;
result1 = c >> b;

// 4 (00000000000000000000000000000100)
console.log(result); 

// -2 (11111111111111111111111111111110)
console.log(result1); 
```
```s
let a = 8;
let b = 1;
let c = -3; 

result = a >>> b;
result1 = c >>> b;

// 4 (00000000000000000000000000000100)
console.log(result);

// 1073741823 (00111111111111111111111111111111)
console.log(result);
```

##### 6. Ternary Operators :
* A ternary operator evaluates a condition and executes a block of code based on the condition.
```s
condition ? expression1 : expression2
```
* The ternary operator evaluates the test condition.

    - If the condition is true, expression1 is executed.
    - If the condition is false, expression2 is executed.

* The ternary operator takes three operands, hence, the name ternary operator. It is also known as a conditional operator.

```s
// program to check pass or fail

let marks = prompt('Enter your marks :');

// check the condition
let result = (marks >= 40) ? 'pass' : 'fail';

console.log(`You ${result} the exam.`);
```
* Ternary Operator Used Instead of if...else
```s
// check the age to determine the eligibility to vote
let age = 15;
let result;

if (age >= 18) {
      result = "You are eligible to vote.";
} else {
      result = "You are not eligible to vote yet.";
}

console.log(result);
```


