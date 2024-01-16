# Inline css

```html
<html>
  <head>
    <title>css inline</title>
  </head>
  <body>
    <h1 style="color: red; text-align: center;">Hallo i am inline style</h1>
  </body>
</html>
```

# Internal css

```html
<html>
  <head>
    <title>css internal</title>
    <style>
      h1 {
        color: red;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <h1>Hallo i am internal style</h1>
  </body>
</html>
```

# External css

```html
<html>
  <head>
    <title>css external</title>
    <!-- external  file link -->
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Hallo i am external style</h1>
  </body>
</html>
```

# CSS Syntex

```html
<html>
  <head>
    <title>css syntex</title>
  </head>
  <style>
    h1 {
      color: red;
      text-align: center;
    }
  </style>
  <body>
    <h1>Hallo i am h1</h1>
  </body>
</html>
```

# CSS COLOR

```html
<html>
  <head>
    <title>css color</title>
  </head>
  <style>
     h1{
            color: green;
           }
           h2{
            color: red;
           }
           p{
            color: brown;
           }
  </style>
  <body>
    h1>Hallo i am  h1</h1>
   <h2>Hallo i am h2</h2>
   <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam, sint?</p>
  </body>
</html>
```

# CSS bg-color

```html
<html>
  <head>
    <title>css bg-color</title>
  </head>
  <style>
         h1{
            color: green;
            background-color: gray;
           }
           h2{
            color: red;
            background-color: yellow;
           }
           p{
            color: brown;
            background-color: tomato;
           }
  </style>
  <body>
    h1>Hallo i am  h1</h1>
   <h2>Hallo i am h2</h2>
   <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam, sint?</p>
  </body>
</html>
```

# CSS margin

```html
<html>
  <head>
    <title>css margin</title>
  </head>
  <style>
              h1{
            color: green;
            background-color: gray;
            margin: 100px;
            margin-left: 10px;
            margin-right: 5px;
            margin-top: 5px;
            margin-bottom: 5px;
           }
           h2{
            color: red;
            background-color: yellow;
            margin:5rem;
            margin-left: 10px;
            margin-right: 5px;
            margin-top: 5px;
            margin-bottom: 5px;
           }
           p{
            color: brown;
            background-color: tomato;
            margin:5% ;
            margin-left: 10px;
            margin-right: 5px;
            margin-top: 5px;
            margin-bottom: 5px;
           }
  </style>
  <body>
    h1>Hallo i am  h1</h1>
   <h2>Hallo i am h2</h2>
   <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam, sint?</p>
  </body>
</html>
```

# CSS padding

```html
<html>
  <head>
    <title>css Padding</title>
  </head>
  <style>
             h1{
            color: green;
            background-color: gray;
            padding: 10px;
            padding-left: 5px;
            padding-bottom: 5px;
            padding-top: 5px;
            padding-bottom: 5px;
           }
           h2{
            color: red;
            background-color: yellow;
            padding:5rem;
            padding-left: 5px;
            padding-bottom: 5px;
            padding-top: 5px;
            padding-bottom: 5px;
           }
           p{
            color: brown;
            background-color: tomato;
            padding:5% ;
            padding-left: 5px;
            padding-bottom: 5px;
            padding-top: 5px;
            padding-bottom: 5px;
           }
  </style>
  <body>
    h1>Hallo i am  h1</h1>
   <h2>Hallo i am h2</h2>
   <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam, sint?</p>
  </body>
</html>
```

# CSS Comments

```html
<html>
  <head>
    <title>css comments</title>
  </head>
  <style>
    /* i am comments  start for css */
    h1 {
      color: red;
      text-align: center;
    }
    /* i am comments  end for css */
  </style>
  <body>
    <!-- i am comments  start for html -->
    <h1>Hallo i am h1</h1>
    <!-- i am comments  end for html -->
  </body>
</html>
```

# CSS Selecotor

```html
<html>
  <head>
    <title>css selecotor</title>
  </head>
  <style>
    /* this is a Universal selecotor start */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    /* this is a Universal selecotor end */
    /* this is a element selecotor for h1 start */
    h1 {
      color: red;
      text-align: center;
    }
    /* this is a element selecotor for h1 end */
    /* this is container for class selector start */
    .container {
      background-color: darkblue;
      height: 100vh;
      width: 1000px;
      margin: 0 auto;
    }
    /* this is container for class selector end */
    /* this is container for id selector start */
    #container {
      background-color: darkblue;
      height: 100vh;
      width: 1000px;
      margin: 0 auto;
    }
    /* this is container for id selector end */
  </style>
  <body>
    <h1>Hallo i am h1</h1>
    <!-- this is container for class selector start -->
    <div class="container"></div>
    <!-- this is container for class selector end -->
    <!-- this is container for id selector start -->
    <div id="container"></div>
    <!-- this is container for id selector end -->
  </body>
</html>
```

# CSS POSITION

```html
<html>
  <head>
    <title>css position</title>
  </head>
  <style>
    /* More position value start */
      - [x]  static
      - [x]  sticky
      - [x]  fixed
      - [x]  relative
      - [x]  absolute

    /* More position value end */
    .first-div {
      background-color: brown;
      width: 400px;
      height: 300px;
      position: relative;
      z-index: 1;
    }
    .second-div {
      background-color: red;
      width: 200px;
      height: 100px;
      position: absolute;
      margin-top: -150px;
      margin-left: 180px;
      z-index: 2;
    }
  </style>
  <body>
    <div class="first-div"></div>
    <div class="second-div"></div>
  </body>
</html>
```
