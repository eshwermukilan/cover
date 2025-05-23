# Ex.06 Book Front Cover Page Design
## Date:15.05.2025
## Name: ESHWER M
## Reg no: 212224040086

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>INTO THE WATER - Book Template</title>
  <style>
    body {
      background:hwb(0 0% 100%);
      font-family: 'Georgia', serif;
      margin: 0;
      padding: 0;
    }
    .book {
      width: 12cm;          /* typical book width */
      height: 18cm;         /* fixed height */
      margin: 50px auto;
      padding: 20px;
      background: #eeff00;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      border: 2px solid #abac9c;
      overflow: hidden;     /* ensure content fits */
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .cover {
      text-align: center;
    }
    .cover img {
      width: 8cm;
      margin-bottom: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    }
    .title {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 5px;
    }
    .author {
      font-size: 18px;
      color: #000000;
      margin-bottom: 15px;
    }
    .description {
      font-size: 15px;
      line-height: 1.4;
      color: #2779dd;
      text-align: justify;
    }
  </style>
</head>
<body>

<div class="book">
  <div class="cover">
    <img src="intothewater.jpg" alt="INTO THE WATER Book Cover">
    <div class="title"><u>Into The Water</u></div>
    <div class="author">By Paula Hawkins</div>
  </div>
  <div class="description">
    Into the Water by Paula Hawkins is a psychological thriller that explores the mysterious deaths of women in a small town's river. When Nel Abbott is found dead in the water, her sister Jules returns to uncover the truth, facing old memories and hidden secrets. As the story unfolds through multiple characters, the book dives into themes of memory, trauma, and how the past never really stays buried.
  </div>
</div>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-05-15 175058.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
