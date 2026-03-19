# Ex02 Commercial Website
## Date:

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TrendLine - Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    
    <header class="header">
        <div class="logo">TrendLine</div>
        <nav class="nav">
            <a href="#">Home</a>
            <a href="#">Products</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

   
    <section class="hero">
        <h1>Welcome to TrendLine</h1>
        <p>Your one-stop shop for trendy fashion and accessories.</p>
        <button>Shop Now</button>
    </section>

    
    <section class="products">
        <h2>Our Best Sellers</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="image1.png" alt="Product 1">
                <h3>Casual Shirt</h3>
                <p>₹799</p>
            </div>
            <div class="product-card">
                <img src="image2.png" alt="Product 2">
                <h3>Leather Bag</h3>
                <p>₹1,999</p>
            </div>
            <div class="product-card">
                <img src="image3.png" alt="Product 3">
                <h3>Shoes</h3>
                <p>₹2,499</p>
            </div>
            <div class="product-card">
                <img src="image.png" alt="Product 4">
                <h3>Watch</h3>
                <p>₹3,499</p>
            </div>
        </div>
    </section>

    <section class="about">
        <h2>About Us</h2>
        <p>At TrendLine, we believe fashion should be accessible and stylish for everyone. We bring you the latest trends at affordable prices.</p>
    </section>

    <footer class="footer">
        <p>Created by Aman Monty | Reg No: 212224040054</p>
    </footer>

</body>
</html>
```
```

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}


.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #222;
    color: #fff;
    padding: 15px 30px;
}
.header .logo {
    font-size: 1.5rem;
    font-weight: bold;
}
.header .nav a {
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
}
.header .nav a:hover {
    text-decoration: underline;
}

.hero {
    background: #f4f4f4;
    text-align: center;
    padding: 60px 20px;
}
.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}
.hero button {
    background: #ff6600;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}
.hero button:hover {
    background: #e65c00;
}

.products {
    padding: 40px 20px;
    text-align: center;
}
.product-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}
.product-card {
    background: white;
    border: 1px solid #ddd;
    padding: 15px;
    width: 200px;
    text-align: center;
}
.product-card img {
    max-width: 100%;
    margin-bottom: 10px;
}
.product-card h3 {
    margin: 10px 0 5px;
}
.product-card p {
    color: green;
    font-weight: bold;
}

.about {
    background: #f9f9f9;
    padding: 30px 20px;
    text-align: center;
}

.footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}
```


## OUTPUT
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/4fc20f6a-0e32-473b-9a22-37efaa14da74" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/61864c67-7840-4f11-9769-434976064ceb" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
