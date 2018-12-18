# frontendapp 🦈

With the following command you will create the settings of your project:
  
    npm init

With the following command you will add the web server globally:
    
    npm install http-server -g


>You  must use a super user if it doesn't work.


You could start the web server to check if everything is ok:
    
    http-server

Now create a folder `src` with two files inside:
    
    touch src/index.html
    touch src/style.css

Now, code time!, add the follow code to index.html:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>my-first-fe-app</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="app">
  </div>
  <script src="index.js"></script>
</body>
</html>
````
add the follow code to style.css:

```Javascript
const node = document.querySelector('.app')
const child = `<p class="love">Tiamo ${15*3}</p>`
node.innerHTML = child
console.log(node)
```

