# Step 1 : collect assets

1. https://www.doubao.com/
2. gen assets from https://www.doubao.com/ using AI tool
3. prompt : `vacation on beach side with palm trees 金色阳光穿透蓝色海面洒落，自然浪漫主义，参考爱德华·霍普冷静孤独光感，比例 「4:3」` for hero image
4. https://favicon.io/favicon-generator/ for favicon

# Step 2 : create gitignore and init git

1. create .gitignore file

```html
./img/*.* .Ds_Store
```

2. git init

# Step 3 : html layout

1. create index.html
   a. include cdn link for fontawesome
   b. include favicon
2. create style.css inside css folder

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.0/css/all.min.css"
      integrity="sha512-DxV+EoADOkOygM4IR9yXP8Sb2qwgidEmeqAEmDKIOfPRQZOWbXCzLC6vjbZyy0vPisbH2SyW27+ddLVCN+OMzQ=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link rel="shortcut icon" href="./img/favicon.ico" type="image/x-icon" />
    <link rel="stylesheet" href="./css/style.css" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

3. cut the layout into sections

# Step 4 : add Navbar

1. copy navbar from hamburger.html
2. add icon-menu section
3. goto fontawesome pick up icons

# Step 5 : add color scheme

1. https://uicolors.app/generate/4f959d
2. color to grey https://pinetools.com/greyscale-desaturate-color
