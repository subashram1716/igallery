# Ex.07 Design of Interactive Image Gallery
## Date:25/12/2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Multiple Images Enlarge on Click</title>
<style>
  .clickable-image {
    width: 150px;
    height: auto;
    margin: 10px;
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  .enlarged {
    transform: scale(2);
    z-index: 10;
    position: relative;
  }
</style>
</head>
<body>
<center>
<img class="clickable-image" src="https://tse4.mm.bing.net/th/id/OIP.EsEOUxTbPhY5rrL7bE2woQHaEK?cb=ucfimg2&ucfimg=1&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Image 1" />
<img class="clickable-image" src="https://tse2.mm.bing.net/th/id/OIP.l8Fu2tkQ8HBiRNEGsUp6pgHaFK?cb=ucfimg2&ucfimg=1&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Image 2" />
<img class="clickable-image" src="https://staticg.sportskeeda.com/editor/2022/10/fd2b9-16652598039107-1920.jpg" alt="Image 3" />
<img class="clickable-image" src="https://tse3.mm.bing.net/th/id/OIP.222YI2V731dSJ3f2w8sqlgHaEK?cb=ucfimg2&ucfimg=1&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Image 4" />
</center>
<script>
  const images = document.querySelectorAll('.clickable-image');

  images.forEach(img => {
    img.addEventListener('click', () => {
      img.classList.toggle('enlarged');
    });
  });
</script>

</body>
</html>
```

## OUTPUT:


<img width="1920" height="1080" alt="528866076-20495f7b-15c5-47e4-aea6-fba2423b1090" src="https://github.com/user-attachments/assets/ede8a987-5739-459e-a247-256263d998f2" />


## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
