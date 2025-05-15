# Ex.06 Book Front Cover Page Design
## Date:15/05/2025
## Name: P KEVIN
## Register no: 212224040159

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: lightgoldenrodyellow;
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
      color: #2e2e2e;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
    }

    .image {
      flex: 1;
      background: url('https://th.bing.com/th/id/OIP.r9cbucrSADdTufezcVvL3AHaF7?w=251&h=200&c=7&r=0&o=5&cb=iwc1&dpr=1.3&pid=1.7.png') center/contain no-repeat;
      margin: 30px 0;
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: #444;
      margin-top: 20px;
    }

    .line {
      height: 2px;
      background: #333;
      width: 50px;
      margin: 10px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">The Psychology of Money </div>
      <div class="line"></div>
      <div class="subtitle">its ability to give you control over your time.</div>
    </div>
    <div class="image">
    </div>
    <div class="author">By Morgan Housel </div>
  </div>
</body>
</html>
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/8bb36a09-6b05-4f5e-bef2-378b5a7fa5d3)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
