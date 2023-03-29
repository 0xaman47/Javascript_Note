### DOM(document object model) Function :
##### document.getElementById()
##### document.getElementByClassName()
##### innerHTML()

##### document.getElementById() :
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
    <div id="main">Welcome to 0xaman47 course</div>
</body>
<script type="text/javascript">
    var x = document.getElementById("main");
    console.log(x);
</script>
</html>
```
##### document.getElementByClassName() :
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
    <div class="main">Welcome to 0xaman47 course</div>
</body>
<script type="text/javascript">
    var x = document.getElementById("main");
    console.log(x);
</script>
</html>
```
##### innerHTML() :
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
    <div id="main">Welcome to 0xaman47 course</div>
</body>
<script type="text/javascript">
    var x = document.getElementById("main").innerHTML = "0xaman47";
    console.log(x);
</script>
</html>
```


