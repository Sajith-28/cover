# Ex.05 Book Front Cover Page Design
## Date:17/10/2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
Name: SAJITH AHAMED F
Reg No: 212223240144
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: black;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .book-cover {
      width: 500px;
      height: 700px;
      background-color: #00ffbf;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      position: relative;
      overflow: hidden;
    }

    .insight {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 15px;
      font-weight: bold;
      color: azure;
      font-family: 'Arial Black', sans-serif;
    }

    .line1,
    .line2,
    .line3 {
      position: absolute;
      width: 80%;
      left: 10%;
    }

    .line1 {
      top: 40px;
    }

    .title1 {
      position: absolute;
      top: 180px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 32px;
      font-weight: bold;
      color: white;
      font-family: 'Arial Black', sans-serif;
    }

    .subtitle1 {
      position: absolute;
      top: 470px;
      left: 20px;
      font-size: 18px;
      font-weight: bold;
      color: white;
      font-family: 'Arial Black', sans-serif;
    }

    .subtitle2,
    .subtitle3 {
      position: absolute;
      left: 20px;
      font-size: 18px;
      font-weight: bold;
      color: white;
      font-family: 'Arial Black', sans-serif;
    }

    .subtitle2 {
      top: 520px;
    }

    .subtitle3 {
      top: 560px;
    }

    .line2 {
      top: 480px;
    }

    .line3 {
      bottom: 38px;
    }

    .author {
      position: absolute;
      bottom: 5px;
      right: 20px;
      font-size: 18px;
      color: whitesmoke;
      font-family: 'Arial Black', sans-serif;
    }

    .end {
      position: absolute;
      bottom: 5px;
      left: 50px;
      font-size: 18px;
      color: white;
      font-family: 'Arial Black', sans-serif;
    }

    .mypic {
      position: relative;
      top: 550px;
      left: 370px;
      width: 120px;
      height: 120px;
      overflow: hidden;
      border-radius: 50%;
    }

    .mypic img {
      width: 100%;
      height: auto;
      object-fit: cover;
    }

    .image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top: 0;
      left: 0;
    }
  </style>
</head>

<body>
  <div class="book-cover">
    <img src="c:\Users\jafil\Downloads\tech.png" alt="Book Cover Image" class="image">
    <div class="insight">Basics of Artificial Intelligence</div>
    <div class="line1"><hr style="color:rgba(133, 192, 237, 0.877)"></div>
    <div class="title1">Unsupervised Learning</div>
    <div class="subtitle1">An Exploration of Machine Learning Methods</div>
    <div class="line2"></div> 
    <div class="subtitle2">Diving into Machine Learning Methods</div>
    <div class="subtitle3">Machine Learning Odyssey</div>
    <div class="line3"><hr style="color:rgb(143, 213, 236)"></div>
    <div class="mypic"><img src="c:\Users\jafil\Pictures\sajith.png" alt="Author's Picture"></div>
    <div class="end">SEC'27</div>
    <div class="author">SAJITH AHAMED F</div>
  </div>
</body>

</html>

```

## OUTPUT:

![Screenshot 2024-11-10 200449](https://github.com/user-attachments/assets/3f1242ad-278b-4f78-8602-1170fd61c47f)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
