# Ex.08 Design of Interactive Image Gallery
## DATE : 19/05/2025
## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>MyGallery</h1>
    </header>
    <main class="gallery">
        <img src="1.webp" alt="Image 1" class="gallery-image">
        <img src="2.webp" alt="Image 2" class="gallery-image">
        <img src="3.webp" alt="Image 3" class="gallery-image">
        <img src="4.jpg" alt="Image 4" class="gallery-image">
        <img src="5.jpg" alt="Image 5" class="gallery-image">
        <img src="6.jpg" alt="Image 6" class="gallery-image">
    </main>

    <div class="lightbox" id="lightbox">
        <div class="pos">
            <button id="cb" class="close">x</button>
        </div>
        <img src="" alt="Expanded View" id="lightboxImg">
        <div class="position">
            <button id="prevBtn" class="nav-button">&lt;</button>
            <button id="nextBtn" class="nav-button">&gt;</button>
        </div>
    </div>

    <footer>
        <p>Designed & Developed by<br>VENKATESAN-R </p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
```

## OUTPUT
![Screenshot 2025-05-20 205247](https://github.com/user-attachments/assets/f28b7f95-8b8e-4532-ad82-db303430ee4e)
![Screenshot 2025-05-20 234945](https://github.com/user-attachments/assets/198a63cf-3d97-4b69-b0c8-3b67f40a4c35)
![Screenshot 2025-05-20 234956](https://github.com/user-attachments/assets/47d4132f-f036-43b9-ad54-6ce14b283f42)



## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
