# Activity-27-CSS-GRID

apply it on 5 pages (ex. list of products,list of employees, list of students, etc) - name your repo CSS_GRID - add documentation on README.md of your repo - Submit github repositories

Deadline: DEC 5



Step 1: Project Structure
You can organize your project files as follows:
CSS_GRID/
│
├── index.html                # Home page to link other pages
├── products.html             # Page with a product list using CSS Grid
├── employees.html            # Page with a list of employees using CSS Grid
├── students.html             # Page with a list of students using CSS Grid
├── gallery.html              # Page with a photo gallery using CSS Grid
├── contact.html              # Page with a contact form using CSS Grid
├── styles.css                # Main CSS file containing Grid styles
└── README.md






Step 2: Create HTML and CSS Files
Here are example layouts, code snippets, and descriptions for each of the pages.



1. Home Page (index.html)
This page links to all other pages.

<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Home</title>
</head>
<body>
    <h1>Welcome to CSS Grid Showcase</h1>
    <ul>
        <li><a href="products.html">List of Products</a></li>
        <li><a href="employees.html">List of Employees</a></li>
        <li><a href="students.html">List of Students</a></li>
        <li><a href="gallery.html">Photo Gallery</a></li>
        <li><a href="contact.html">Contact Form</a></li>
    </ul>
</body>
</html>





2. Products List (products.html)
This page displays a grid of products.

<!-- products.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>List of Products</title>
</head>
<body>
    <h1>Products</h1>
    <div class="grid-container">
        <div class="grid-item">Product 1</div>
        <div class="grid-item">Product 2</div>
        <div class="grid-item">Product 3</div>
        <div class="grid-item">Product 4</div>
        <div class="grid-item">Product 5</div>
        <div class="grid-item">Product 6</div>
    </div>
</body>
</html>



3. Employees List (employees.html)
This page displays employee cards.

<!-- employees.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>List of Employees</title>
</head>
<body>
    <h1>Employees</h1>
    <div class="grid-container">
        <div class="grid-item">Employee 1</div>
        <div class="grid-item">Employee 2</div>
        <div class="grid-item">Employee 3</div>
        <div class="grid-item">Employee 4</div>
    </div>
</body>
</html>






4. Students List (students.html)
This page showcases student profiles.

<!-- students.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>List of Students</title>
</head>
<body>
    <h1>Students</h1>
    <div class="grid-container">
        <div class="grid-item">Student 1</div>
        <div class="grid-item">Student 2</div>
        <div class="grid-item">Student 3</div>
        <div class="grid-item">Student 4</div>
        <div class="grid-item">Student 5</div>
    </div>
</body>
</html>






5. Photo Gallery (gallery.html)
A grid layout for images.

<!-- gallery.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Photo Gallery</title>
</head>
<body>
    <h1>Gallery</h1>
    <div class="grid-container">
        <div class="grid-item">Image 1</div>
        <div class="grid-item">Image 2</div>
        <div class="grid-item">Image 3</div>
        <div class="grid-item">Image 4</div>
    </div>
</body>
</html>








6. Contact Form (contact.html

A simple contact form structured with CSS Grid.


<!-- contact.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Contact Form</title>
</head>
<body>
    <h1>Contact Us</h1>
    <form class="grid-container">
        <div class="grid-item"><label for="name">Name:</label></div>
        <div class="grid-item"><input type="text" id="name" name="name"></div>
        <div class="grid-item"><label for="email">Email:</label></div>
        <div class="grid-item"><input type="email" id="email" name="email"></div>
        <div class="grid-item"><input type="submit" value="Submit"></div>
    </form>
</body>
</html>




  Style the Pages with CSS (styles.css)
  
Here’s how to style the pages using CSS Grid:

* {
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 10px;
}

.grid-item {
    background-color: #f1f1f1;
    border: 1px solid #ccc;
    padding: 20px;
    text-align: center;
    border-radius: 5px;
}

form {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 10px;
}








(CSS_GRID)

This repository showcases different layouts using CSS Grid. The project includes five pages demonstrating how to use CSS Grid for responsive design.

## Pages Included

1. **Home**: Links to all other pages.
2. **List of Products**: Displays products in a grid layout.
3. **List of Employees**: Shows employee cards in a grid layout.
4. **List of Students**: Displays student profiles in a grid.
5. **Gallery**: A photo gallery organized with CSS Grid.
6. **Contact Form**: A simple contact form designed with Grid.

## How to View

Clone this repository and open the HTML files in your web browser.

## Technologies Used

- HTML5
- CSS3




AND THE LAST

Commit and Push to GitHub
Open your terminal or command prompt.
Navigate to your project folder containing the files.
Run the following commands to initialize git, add, commit, and push the files to your GitHub repository:



git init
git add .
git commit -m "Initial commit for CSS Grid project"
git branch -M main
git remote add origin https://github.com/yourusername/CSS_GRID.git
git push -u origin main





