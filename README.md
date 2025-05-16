# Ex.04 Book Front Cover Page Design
## Date: 02.05.2025

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
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Book Cover</title>
        <style>
            body {
                background: #f0f0f0;
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
                margin: 0;
            }
    
            .cover {
                background: url('/static/background.png.png') no-repeat center center;
                background-size: cover;
                width: 400px;
                height: 600px;
                border-radius: 20px;
                padding: 40px 30px;
                position: relative;
                box-shadow: 0 4px 15px rgba(0,0,0,0.2);
                font-family: Arial, sans-serif;
            }
    
            h1 {
                font-size: 28px;
                font-weight: bold;
                margin-top: 70px; 
                text-align: center;
                color: #800000; 
            }
    
            .subtitle {
                font-style: italic;
                font-size: 15px;
                margin-top: 10px; 
                text-align: center;
                color: #000000; 
            }
    
            .author-section {
                position: absolute;
                bottom: 60px; 
                right: 30px;
                display: flex;
                flex-direction: column;
                align-items: center;
            }
    
            .author-photo {
                border-radius: 50%;
                width: 100px;
                height: 100px;
                object-fit: cover;
                border: 3px solid white;
            }
    
            .author-name {
                margin-top: 10px;
                color: red; 
                font-weight: bold;
                font-size: 14px;
                text-align: center;
                word-wrap: break-word;
            }
    
            .footer-left {
                position: absolute;
                bottom: 40px;
                left: 20px;
                font-weight: bold;
                color: red;
            }
    
            .footer-right {
                position: absolute;
                bottom: 40px;
                right: 20px;
                font-size: 12px;
                font-weight: 600;
                color: #000080; 
            }
        </style>
    </head>
    <body>
        <div class="cover">
            <h1>Learn Web Development</h1>
            <p class="subtitle">An easy guide to build beautiful websites with HTML and CSS</p>
    
            <div class="author-section">
                <img src="/static/photo.jpg.png" alt="Author Photo" class="author-photo">
                <div class="author-name">Hari Priya M</div>
            </div>
    
            <div class="footer-left">First Edition</div>
            <div class="footer-right">SEC Publications</div>
        </div>
    </body>
    </html>



## OUTPUT:
![Screenshot 2025-05-03 140148](https://github.com/user-attachments/assets/1b1183a6-79da-4377-856e-3e844ba445ac)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
