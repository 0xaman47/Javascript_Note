### What is variable?
* A JavaScript variable is simply a name of storage location.
* variable are container which hold reusable data.
* it is the basic unit of storage in a program.
* the value stored in a variable can be changed during program excitation.
#### Some rule of js :
1. Name must start with a letter (a to z or A to Z), underscore( _ ), or dollar( $ ) sign.
2. After first letter we can use digits (0 to 9), for example value1.
3. JavaScript variables are case sensitive, for example x and X are different variables.

```s
var name;
alert(name);
```
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>array</title>
</head>
<body>
    
</body>
<script>
    var name;
    name = "0xaman47";
    alert (name);
</script>
</html>
```
### Scope and life time of a variable :
##### Scope of a variable :
* variable declared within a function are local to that function.
* variables declared outside of any function are global variables.
##### Life time of a variable :
* local variable's life time is within the block of its declaration.
* Global variable's life time is throughout the program.