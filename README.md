# Ex.06 Book Front Cover Page Design
## Date: 28/10/2025

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
      font-family: 'Segoe UI', sans-serif;
    }

    .bookpage {
      width: 400px;
      height: 600px;
      padding: 40px 30px;
      color: #333;
      background-image: url('back.jpeg');
      background-size: cover;
      background-position: center;
      border-radius: 12px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
      position: relative;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    /* Overlay for readability */
    .overlay {
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(255, 255, 255, 0.65);
      border-radius: 12px;
      z-index: 0;
    }

    .content {
      position: relative;
      z-index: 1;
      display: flex;
      flex-direction: column;
      height: 100%;
      justify-content: space-between;
    }

    .top-section {
      text-align: left;
    }

    .insight {
      font-size: 12px;
      color: #5e5e5e;
      letter-spacing: 1px;
    }

    .booktitle {
      font-size: 26px;
      font-weight: 800;
      margin-top: 20px;
      color: #1e293b;
      line-height: 1.4;
    }

    .subtitle {
      margin-top: 10px;
      font-size: 14px;
      color: #555;
      line-height: 1.5;
    }

    .edition {
      margin-top: 25px;
      font-weight: bold;
      color: #b56576;
      font-size: 15px;
    }

    .bottom-section {
      display: flex;
      justify-content: space-between;
      align-items: flex-end;
    }

    .author {
      font-size: 15px;
      font-weight: 700;
      color: #2c3e50;
      text-transform: uppercase;
    }

    .mypic img {
      width: 75px;
      height: 75px;
      border-radius: 50%;
      object-fit: cover;
      border: 2px solid #fff;
      box-shadow: 0 0 6px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <div class="bookpage">
    <div class="overlay"></div>
    <div class="content">
      <div class="top-section">
        <div class="insight">EXPERT INSIGHT</div>
        <div class="booktitle">
          All about Web<br>Design with<br>HTML5 and CSS
        </div>
        <div class="subtitle">
          Develop future-proof responsive websites<br>using the latest HTML5 and CSS techniques
        </div>
        <div class="edition">Third Edition</div>
      </div>

      <div class="bottom-section">
        <div class="author">M RESHIKA</div>
        <div class="mypic">
          <img src="author.jpg" alt="Author">
        </div>
      </div>
    </div>
  </div>
</body>
</html>
```

## OUTPUT:
<img width="1902" height="1085" alt="Screenshot 2025-10-28 131325" src="https://github.com/user-attachments/assets/2d1a256f-4b36-452f-9207-f60ac554f8a7" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
