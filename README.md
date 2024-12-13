# Ex.06 Book Front Cover Page Design
# Date: 28/10/2024
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
        background-color: #f4f4f4;
      }
      .book-cover {
        width: 300px;
        height: 550px;
        background-color: hwb(0 2% 90% / 0.298);
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        position: relative;
        overflow: hidden;
        padding: 20px;
        box-sizing: border-box;
        display: flex;
        flex-direction: column;
        align-items: center;
      }
      .book-cover img {
        width: 100%;
        height: auto;
        margin-top: 20px; /* Adds space above the image */
        image-color:rgba(0, 0, 0, 0.1);
      }
      .book-info {
        text-align: center;
        margin-bottom: 20px; /* Space below the text */
      }
      .book-title {
        font-size: 25px;
        font-weight: bold;
      }
      .book-author {
        font-size: 12px;
        margin: 5px 0;
        margin-left: 100px;
      }
      .description {
        font-size: 12px;
        font-family: 'Times New Roman', Times, serif;
        max-height: 40px; /* Limit height for overflow */
        overflow: hidden;
        text-overflow: ellipsis;
      }
    </style>
    </head>
    <body>
    
    <div class="book-cover">
      <div class="book-info">
        <h1 class="book-title">"HEART AND MIND: THE BATTLE OF CONSCIOUSNESS"</h1>
        <p class="book-author">- NOAH SALVATORE</p>
        <p class="description">"Heart and Mind: The Battle of Consciousness" delves into
             the intricate dance between our emotional and rational selves.</p>
      </div>
      <img src="heart.jpg" alt="Cover of Heart and Mind: The Battle of Consciousness">
    </div>
    
    </body>
    </html>
    
# OUTPUT
![image](https://github.com/user-attachments/assets/8db422e5-9d2b-408b-b2f1-ba113a3d2748)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
