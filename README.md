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
    h1 {
      color: green;
    }
    h2 {
      color: red;
    }
    p {
      color: brown;
    }
  </style>
  <body>
    <h1>Hallo i am h1</h1>
    <h2>Hallo i am h2</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam, sint?
    </p>
  </body>
</html>
```

# CSS TEXT

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Css-text</title>
    <style>
      h1 {
        color: green;
      }
      h2 {
        text-align: center;
        /* text-align-last: justify;
              text-align-last: left;
              text-align-last: right;
              text-align-last: center;
            */
      }
      h3 {
        text-decoration: underline;
        /* text-decoration: overline;
            text-decoration: line-through;
           text-decoration-color: brown;
           text-decoration-style: dotted;
           text-decoration-thickness:auto; */
      }
      h4 {
        text-transform: uppercase;
        /* text-transform: lowercase;
            text-transform: capitalize; */
      }
      h5 {
        text-indent: 50px;
        /* letter-spacing: 5px;
           line-height: 20px;
           word-spacing: 10px;
           white-space: nowrap; */
      }
      h6 {
        text-shadow: 2px 2px 2px red;
      }
    </style>
  </head>
  <body>
    <h1>I am color</h1>
    <h2>I am align</h2>
    <h3>I am decoration</h3>
    <h4>I am transformation</h4>
    <h5>I am spacing</h5>
    <h6>I am shadow</h6>
  </body>
</html>
```

# CSS FONTS

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Css-fonts</title>
    <!-- google font cdn -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto&display=swap"
      rel="stylesheet"
    />
    <style>
      h1 {
        font-family: "Times New Roman", Times, serif;
      }
      h2 {
        font-style: normal;
        font-style: italic;
      }
      h3 {
        font-size: 30px;
      }
      h4 {
        font-family: "Roboto", sans-serif;
      }
    </style>
  </head>
  <body>
    <h1>I am font-family</h1>
    <h2>I am font-style</h2>
    <h3>I am font-size</h3>
    <h4>I am Google Fonts</h4>
  </body>
</html>
```
# CSS icon
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS-ICON</title>
    <!-- Font awesome cdn  -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
      integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <!-- my internal style start -->
    <style>
      i {
        font-size: 100px;
      }
    </style>
    <!-- my internal style end -->
  </head>
  <body>
    <!-- font awesome icon -->
    <i class="fa-brands fa-html5"></i>
    <i class="fa-brands fa-css3-alt"></i>
    <i class="fa-brands fa-bootstrap"></i>
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
    h1 {
      color: green;
      background-color: gray;
    }
    h2 {
      color: red;
      background-color: yellow;
    }
    p {
      color: brown;
      background-color: tomato;
    }
  </style>
  <body>
    <h1>Hallo i am h1</h1>
    <h2>Hallo i am h2</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam, sint?
    </p>
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
    h1 {
      color: green;
      background-color: gray;
      margin: 100px;
      margin-left: 10px;
      margin-right: 5px;
      margin-top: 5px;
      margin-bottom: 5px;
    }
    h2 {
      color: red;
      background-color: yellow;
      margin: 5rem;
      margin-left: 10px;
      margin-right: 5px;
      margin-top: 5px;
      margin-bottom: 5px;
    }
    p {
      color: brown;
      background-color: tomato;
      margin: 5%;
      margin-left: 10px;
      margin-right: 5px;
      margin-top: 5px;
      margin-bottom: 5px;
    }
  </style>
  <body>
    <h1>Hallo i am h1</h1>
    <h2>Hallo i am h2</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam, sint?
    </p>
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
    h1 {
      color: green;
      background-color: gray;
      padding: 10px;
      padding-left: 5px;
      padding-bottom: 5px;
      padding-top: 5px;
      padding-bottom: 5px;
    }
    h2 {
      color: red;
      background-color: yellow;
      padding: 5rem;
      padding-left: 5px;
      padding-bottom: 5px;
      padding-top: 5px;
      padding-bottom: 5px;
    }
    p {
      color: brown;
      background-color: tomato;
      padding: 5%;
      padding-left: 5px;
      padding-bottom: 5px;
      padding-top: 5px;
      padding-bottom: 5px;
    }
  </style>
  <body>
    <h1>Hallo i am h1</h1>
    <h2>Hallo i am h2</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam, sint?
    </p>
  </body>
</html>
```

# height and width

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Css-height and width</title>
    <style>
      .first {
        width: 500px;
        height: 400px;
      }
      .second {
        width: 50%;
        height: 30%;
      }
    </style>
  </head>
  <body>
    <p class="first">
      only width <br />
      Lorem ipsum dolor sit amet consectetur adipisicing elit. In quam, sunt cum
      beatae tenetur suscipit, corporis, distinctio necessitatibus eveniet
      magnam culpa provident natus! Earum, minus est. Dolorem assumenda ad
      corrupti quos maiores rem est deserunt aspernatur nesciunt neque quas
      mollitia quis voluptate voluptatibus, deleniti nam explicabo maxime
      impedit, fugit repudiandae. Natus corporis labore nesciunt sequi sunt
      dolorum tenetur eligendi eaque laudantium voluptas, modi amet at debitis
      alias! Asperiores perferendis fuga iste natus dolore, recusandae rerum
      accusantium? Eligendi, repellat aliquid pariatur quisquam blanditiis
      doloribus consectetur est, ab id repellendus harum sapiente vero aperiam
      nemo ut et voluptate reiciendis ratione dignissimos eum?
    </p>
    <p class="second">
      max-width <br />
      Lorem ipsum dolor sit amet consectetur adipisicing elit. In quam, sunt cum
      beatae tenetur suscipit, corporis, distinctio necessitatibus eveniet
      magnam culpa provident natus! Earum, minus est. Dolorem assumenda ad
      corrupti quos maiores rem est deserunt aspernatur nesciunt neque quas
      mollitia quis voluptate voluptatibus, deleniti nam explicabo maxime
      impedit, fugit repudiandae. Natus corporis labore nesciunt sequi sunt
      dolorum tenetur eligendi eaque laudantium voluptas, modi amet at debitis
      alias! Asperiores perferendis fuga iste natus dolore, recusandae rerum
      accusantium? Eligendi, repellat aliquid pariatur quisquam blanditiis
      doloribus consectetur est, ab id repellendus harum sapiente vero aperiam
      nemo ut et voluptate reiciendis ratione dignissimos eum?
    </p>
  </body>
</html>
```

# MAX-WIDTH

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Css-max-width</title>
    <style>
      .first {
        border: 1px solid green;
        width: 500px;
      }
      .second {
        border: 1px solid green;
        max-width: 500px;
      }
    </style>
  </head>
  <body>
    <p class="first">
      only width <br />
      Lorem ipsum dolor sit amet consectetur adipisicing elit. In quam, sunt cum
      beatae tenetur suscipit, corporis, distinctio necessitatibus eveniet
      magnam culpa provident natus! Earum, minus est. Dolorem assumenda ad
      corrupti quos maiores rem est deserunt aspernatur nesciunt neque quas
      mollitia quis voluptate voluptatibus, deleniti nam explicabo maxime
      impedit, fugit repudiandae. Natus corporis labore nesciunt sequi sunt
      dolorum tenetur eligendi eaque laudantium voluptas, modi amet at debitis
      alias! Asperiores perferendis fuga iste natus dolore, recusandae rerum
      accusantium? Eligendi, repellat aliquid pariatur quisquam blanditiis
      doloribus consectetur est, ab id repellendus harum sapiente vero aperiam
      nemo ut et voluptate reiciendis ratione dignissimos eum?
    </p>
    <p class="second">
      max-width <br />
      Lorem ipsum dolor sit amet consectetur adipisicing elit. In quam, sunt cum
      beatae tenetur suscipit, corporis, distinctio necessitatibus eveniet
      magnam culpa provident natus! Earum, minus est. Dolorem assumenda ad
      corrupti quos maiores rem est deserunt aspernatur nesciunt neque quas
      mollitia quis voluptate voluptatibus, deleniti nam explicabo maxime
      impedit, fugit repudiandae. Natus corporis labore nesciunt sequi sunt
      dolorum tenetur eligendi eaque laudantium voluptas, modi amet at debitis
      alias! Asperiores perferendis fuga iste natus dolore, recusandae rerum
      accusantium? Eligendi, repellat aliquid pariatur quisquam blanditiis
      doloribus consectetur est, ab id repellendus harum sapiente vero aperiam
      nemo ut et voluptate reiciendis ratione dignissimos eum?
    </p>
  </body>
</html>


```

# box-sizing

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>box-sizing</title>
    <style>
      .first {
        width: 300px;
        height: 200px;
        margin: 10px;
        box-sizing: border-box;
        border: 4px solid black;
        background-color: yellowgreen;
      }
      .last {
        width: 300px;
        height: 200px;
        margin: 10px;
        border: 4px solid black;
        background-color: yellowgreen;
      }
    </style>
  </head>
  <body>
    <div class="first"></div>
    <div class="last"></div>
  </body>
</html>
```

# box model

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>box-model</title>
    <style>
      .first {
        width: 300px;
        margin: 5px;
        padding: 5px;
      }
      .last {
        width: 300px;
        margin-left: 10px;
      }
    </style>
  </head>
  <body>
    <div class="first">this is first div</div>
    <div class="last">this is last div</div>
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
       - [x] fixed 
       - [x] relative
       - [x] absolute 
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

# CSS Overflow

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS-Overflow</title>
    <style>
      p {
        width: 400px;
        height: 300px;
        background-color: black;
        color: white;
        font-size: 1.3rem;
        /* overflow: scroll; */
        /* overflow: hidden; */
        overflow: auto;
      }
    </style>
  </head>
  <body>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro laboriosam,
      sint quisquam nesciunt iusto consequatur velit dolore dicta recusandae
      amet explicabo veritatis atque beatae error alias, debitis, provident
      reiciendis vero! Neque architecto quaerat dolorem similique nisi
      doloremque. Fugit, eligendi! Repudiandae excepturi repellendus pariatur
      rem? Inventore temporibus ducimus provident ullam obcaecati accusantium,
      sint odit totam rem reprehenderit cupiditate molestias corporis, fugit
      culpa itaque assumenda quo alias eos distinctio excepturi similique
      debitis expedita dolores. Repellendus incidunt tempora nihil odio aliquid
      rem. Velit cumque corporis vitae praesentium officiis eaque, quam nesciunt
      obcaecati molestiae reiciendis minima perferendis sed delectus
      necessitatibus quaerat iure libero iste.
    </p>
  </body>
</html>
```

# CSS Float

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS-Float</title>
    <style>
      h1 {
        float: left;
      }
      h2 {
        float: right;
      }
      p::before {
        content: " ";
        clear: both;
        display: table;
      }
    </style>
  </head>
  <body>
    <h1>I am left</h1>
    <h2>I am right</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus eaque
      quam aspernatur corrupti ratione corporis harum illum veniam dolor.
      Molestias.
    </p>
  </body>
</html>
```

# CSS-inline-block

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS-inline-block</title>
    <style>
      h1 {
        background-color: green;
        display: block;
      }

      h2 {
        background-color: red;
        display: inline;
      }
      p {
        background-color: darkblue;
        display: inline-block;
      }
    </style>
  </head>
  <body>
    <h1>I am block</h1>
    <h2>I am inline</h2>
    <p>i am inline-block</p>
  </body>
</html>
```

# CSS align

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS-align</title>
    <style>
      h1 {
        background-color: green;
        height: 300px;
        width: 500px;
        text-align: center;
      }

      h2 {
        background-color: red;
        height: 300px;
        width: 500px;
        margin: auto;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <h1>I am block</h1>
    <h2>I am inline</h2>
  </body>
</html>
```
