___
### Looping statement :
#### What is loop?
* A loop is used to repeat a block of code until the specified condition is met.
* when similar task is needed to be done again and again.
* save time and leads to code reusability.
  ```mermaid
  flowchart TD;
  Loop--> For_loop;
  Loop--> While_loop;
  Loop--> DO_while_loop
  Loop--> foreach;
  ```
#### For loop :
```s
for(initialization;test condition;+ement/-ement){
    //condition
}
```  
``` html
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
    for(var cout = 10;cout >= 1;cout--){
        document.write(cout+". Welcome to 0xaman47 course<br>");
    }
</script>
</html>
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
    for(var cout = 1;cout <= 10;cout++){
        document.write(cout+". Welcome to 0xaman47 course<br>");
    }
</script>
</html>
```
#### While loop :
#### What is while loop?
* A while loop is to executed a statement or code block repeatedly as long as condition is true.
* Once the condition become false, the loop terminates.
* it is also called entry control loop.
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
    var cout=1;
    while(cout <= 10){
        document.write(cout+". Welcome to 0xaman47 course<br>");
        cout++;
    }
</script>
</html>
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
    var cout=10;
    while(cout >= 0){
        document.write(cout+". Welcome to 0xaman47 course<br>");
        cout--;
    }
</script>
</html>
```
### Do While loop :
* The JavaScript do while loop iterates the elements for the infinite number of times like while loop. But, code is executed at least once whether condition is true or false
  ```syntax```
  ```s
     do{  
       // code to be executed  
    }while (condition);   
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
    var i=1;
    do{
        document.write(i+"<br>");
        i++;
    }while(i<=10);

</script>
</html>
```
### ForEach Loop :
#### What is ForEach loop?
* A ForEach loop (method) is used to get data from JS array or object.
* The method calls a function once for each element in an array,in order.
```Syntax```
```s
var cars = ["car1","car2","car3"];
car.forEach(myfunction);

function myfunction(item,index,array){
    // body of function
}
```
```note```
> item : (here"car1) required parameter
> index : (here 0 for "car1") optional
> Array : (here cars) optional
```Code```
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
    var cars = ["car1","car2","car3","car4"];
    cars.forEach(car);
    function car(item,index,array){
         //document.write(index+" => "+item+" <br>");
         array[index] = item+" 0";
    }    
    cars.forEach(after);
    function after(item,index){
        document.write(index+" => "+item+" <br>");
    }

</script>
</html>
```

