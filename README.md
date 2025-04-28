# Ex.06 Book Front Cover Page Design
## Date:27-04-2025

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

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Book Cover</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        background-color: #6426ea;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        font-family: "Georgia", serif;
      }

      .book-cover {
        width: 400px;
        height: 600px;
        /* background: #64FDFF; */
        background-image: url(bg-img.png);
        border: 2px solid #333;
        padding: 40px 30px;
        box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
        display: flex;
        flex-direction: column;
        justify-content: space-between;
      }

      .title {
        font-size: 28px;
        font-weight: bold;
        color: white;
        text-align: center;
        line-height: 1.3;
      }

      .subtitle {
        font-size: 16px;
        margin-top: 10px;
        text-align: center;
        font-style: italic;
        color: white;
      }

      .image {
        flex: 1;
        background: url("https://upload.wikimedia.org/wikipedia/commons/6/65/Simple_flowers_black_line_art.png")
          center/contain no-repeat;
        margin: 80px 0;
      }

      .author {
        font-size: 18px;
        text-align: center;
        color: #fff;
        margin-top: 20px;
      }

      .line {
        height: 2px;
        background: #333;
        width: 50px;
        margin: 5px auto;
      }
    </style>
  </head>
  <body>
    <div class="book-cover">
      <div>
        <div class="title">RAIN DROP</div>
        <div class="line"></div>
        <div class="subtitle">The Life Of Earth</div>
      </div>
      <div class="image">
        <img src="RAIN DROP.jpg" length="20%" width="100%" />
      </div>
      <div class="author">By PRAVEEN SANTHALINGAM M</div>
    </div>
  </body>
</html>

## OUTPUT:

![image](https://github.com/user-attachments/assets/ac0d4538-f668-4c4f-9e99-bb9710c3bb03)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
