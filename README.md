# Ex02 Commercial Website
## Date:23/2/2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Studio Union</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
    <a href="#account">Account</a>
</nav>

<section id="home">
    <h2>Welcome</h2>
    <p>This is a simple commercial website created using Flexbox.</p>
</section>

<section id="products">
    <h2>Our Products</h2>
    <div class="product-container">
        <div class="box">Product 1</div>
        <div class="box">Product 2</div>
        <div class="box">Product 3</div>
    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>We provide good quality products at affordable prices.</p>
</section>

<section id="contact">
    <h2>Contact Details</h2>
    <p>Email: stunio@gmail.com</p>
    <p>Phone: 9876543210</p>
</section>

<section id="account">
    <h2>User Account</h2>
    <button>Login</button>
    <button>Register</button>
</section>

<footer>
    <p>Follow us on Facebook | Instagram | Twitter</p>
    <p>© 2026 My Online Store</p>
</footer>

</body>
</html>
```

style.css
```
body {
    font-family: Arial;
    margin: 0;
}

header {
    background-color: darkblue;
    color: white;
    text-align: center;
    padding: 15px;
}

nav {
    background-color: lightgray;
    padding: 10px;
    text-align: center;
}

nav a {
    margin: 10px;
    text-decoration: none;
    color: black;
}

nav a:hover {
    color: red;
}

section {
    padding: 20px;
    text-align: center;
}

.product-container {
    display: flex;
    justify-content: space-around;
    margin-top: 15px;
}

.box {
    background-color: lightblue;
    padding: 20px;
    width: 120px;
    border: 1px solid gray;
}

.box:hover {
    background-color: skyblue;
}

footer {
    background-color: black;
    color: white;
    text-align: center;
    padding: 10px;
}
```

## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/83e5fe7c-9dad-44b1-a134-52de2bace161" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
