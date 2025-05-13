# Ex.06 Book Front Cover Page Design
## Name: Renick Fabian Rajesh
## Reg No: 212224230227
## Date: 13/05/2025

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
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover Page</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #f5f5f5; 
    }

    .bookpage {
      width: 400px;
      height: 600px;
      color: #333; 
      padding: 20px;
      background-image: url('back.jpg'); 
      background-size: cover;
      background-position: center;
      font-family: 'Segoe UI', sans-serif;
      position: relative;
      box-shadow: 0 0 20px rgba(0,0,0,0.2);
      background-color: rgba(255, 255, 255, 0.8);
    }

    .insight {
      font-size: 12px;
      color: #5e5e5e; 
      letter-spacing: 1px;
    }

    .booktitle {
      font-size: 24px;
      font-weight: bold;
      margin-top: 30px;
      line-height: 1.4;
      color: #2c3e50; 
    }

    .subtitle {
      margin-top: 10px;
      font-size: 14px;
      color: #6c757d; 
    }

    .edition {
      margin-top: 40px;
      font-weight: bold;
      color: #b56576; 
    }

    .author {
      position: absolute;
      bottom: 40px;
      left: 20px;
      font-size: 16px;
      color: #4d4d4d;
      font-weight: bold;
    }

    .publisher {
      position: absolute;
      bottom: 40px;
      right: 20px;
      font-size: 20px;
      font-weight: bold;
      color: #2a2a2a;
    }

    .mypic img {
      position: absolute;
      bottom: 20px;
      right: 20px;
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      border: 2px solid #ccc; 
    }

    .wave {
      position: absolute;
      top: 200px;
      left: 0;
      right: 0;
      height: 100px;
      background: url('wave.png'); 
      background-size: contain;
      background-repeat: no-repeat;
      background-position: center;
      opacity: 0.6; 
    }
  </style>
</head>
<body>
  <div class="bookpage">
    <div class="insight">EXPERT INSIGHT</div>
    <div class="booktitle">
      All about Web<br>Design with<br>HTML5 and CSS
    </div>
    <div class="subtitle">
      Develop future-proof responsive websites<br>using the latest HTML5 and CSS techniques
    </div>
    <div class="edition">Third Edition</div>
    <div class="wave"></div>
    <div class="author">RENICK FABIAN RAJESH</div>
    <div class="publisher">Packt</div>
    <div class="mypic">
      <img src="author.png" alt="Author">
    </div>
  </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-05-13 155613-1.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
