# Starter Project

## What are we doing today?

>1. [Learning to host a static website](#hosting-a-static-webpage)
>1. [Adding Html, Css and Javascript to your website](#adding-html-css-and-javascript-to-your-website)
>1. [Creating a favicon](#creating-a-favicon)

## Hosting a static webpage

### 1. Create a repository with the standard template

![repo](documentation\images\1.png)

### 2. Go to Settings --> Pages -->  Github Actions

![repo](documentation\images\2.png)

### 3. Under 'Static HTML' , select configure and commit your changes

![repo](documentation\images\3.png)

### 4. Your static website has been deployed

![repo](documentation\images\4.png)

## Adding Html, Css and Javascript to your website

### 1. Clone your repository and open in VS code

![repo](documentation\images\5.png)

![repo](documentation\images\6.png)

### 2. Create the folder and file structure as shown below

![repo](documentation\images\7.png)

### 3. Code for 'index.html'

``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="styles.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
      integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <title>Cafe Emerald</title>
  </head>
  <body>
    <div>
      <h1>Maryam's coffee shop <i class="fa-brands fa-apple"></i></h1>
    </div>

    <script src="script.js"></script>
  </body>
</html>
```

### 4. Code for 'styles.css'

```css
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@900&display=swap');

* {
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', 'Montserrat', sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 100vh;
    justify-content: center;
    overflow: hidden;
    margin: 0;
}

h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: #1C1678;
}

i {
    font-size: 5rem;
    margin-bottom: 1rem;
    color: blueviolet;
}
```

### 5. Code for 'script.js'

```js
console.log(`${Date()} :: This is a starter template for a simple web app.`);
```

### 6. Under Settings --> Pages, you will see the link to your website

![repo](documentation\images\8.png)

### 7. Your first website is ready

![repo](documentation\images\9.png)

## Creating a favicon

### 1. Create your favicon from here <https://favicon.io>

### 2. Put your favicon in the src folder

### 3. Add this code in the head of your html page

```html
<link rel="icon" href="favicon.ico" type="image/x-icon" />
```

### 4. Your website now has it's own favicon

![repo](documentation\images\10.png)
