# Ex.08 Design of Interactive Image Gallery

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
![alt text](<Screenshot 2025-05-20 205247.png>)

## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
