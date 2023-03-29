___
___
### Array : 
#### What is Array?
* Array ia a group of continuous memory location.
* it ia used to store multiple values into single variable.

#### Way to declaration anm array in js
```Method 1```
> var house=[ ];
> >// initializing while declaring 
> >var house = ["1BHK","2BHK","3BHK"];
> >>// initializing after declaring.
> >> house[0] = "1BHK";
> >> house[1] = "2BHK";
> >> house[2] = "3BHK";
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
    var car = [];
    car = ["car1","car2","car3"];
    document.write(car[1]);
</script>
</html>
``` 

```Method 2```
> var house = newarray();
> > // create an array 
> > var house = new Array(10,20,30);
> >>// storing number,string in an Array
> >>var house = ["1BHK",5000,"2BHK",10000];
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
    var cars = new Array();
    cars = ["car1","car2","car3"];
    document.write(cars[2]);
</script>
</html>
```
