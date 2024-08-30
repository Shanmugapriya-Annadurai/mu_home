//html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home -Muu Furniture Store</title>
    <link rel="stylesheet" href="/CSS/Home.css"> 
</head>
<body>

<header>
    <div class="container">
        <h1><a href="Home.html">Muu Furniture Store</a></h1>
        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="login.html">Login</a></li>
            </ul>
        </nav>
    </div>
</header>

<section class="hero">
    <div class="container">
        <h2>Welcome to our Furniture Store</h2>
        <p>Discover a wide range of stylish and affordable furniture pieces for your home.</p>
        <a href="gallery.html" class="btn">Explore Now</a>
    </div>
</section>

<section class="featured-products">
    <div class="container">
        <h2>Featured Products</h2>
        <div class="product">
            <img src="/Source/pillow-sofa-decoration-interior-living-room-area.jpg" alt="Product 1">
            <h3>Modern Leather Sofa</h3>
          
            <a href="#" class="btn">View Details</a>
        </div>
        <div class="product">
            <img src="/Source/high-angle-dining-table-background-zoom-calls.jpg" alt="Product 2">
            <h3>Wooden Dining Table Set</h3>
        
            <a href="#" class="btn">View Details</a>
        </div>
        
    </div>
</section>

<footer>
    <div class="container">
        <p>&copy; 2024 Muu Furniture Store. All rights reserved.</p>
       
    </div>
</footer>

</body>
</html>




//css code


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Header */
header h1 a {

    color: #fff;
    text-decoration: none;
}
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}
header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline-block;
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Hero Section */
.hero {
    background-image: url('/Source/gray-sofa-brown-living-room-with-copy-space.jpg');
    background-size:cover;
    color: hsl(0, 0%, 100%);
    text-align: center;
    padding: 100px 0;
}

.hero h2 {
    font-size: 3em;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2em;
    margin-bottom: 40px;
}

.hero .btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #f39c12;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

.hero .btn:hover {
    background-color: #e67e22;
}

/* Featured Products Section */
.featured-products {
    padding: 50px 0;
    text-align: center;
}

.featured-products .product {
    display: inline-block;
    width: 300px;
    margin: 0 20px;
    text-align: left;
}

.featured-products .product img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

.featured-products .product h3 {
    margin-top: 10px;
}



.featured-products .product .btn {
    display: block;
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #f39c12;
    color: #fff;
    text-decoration: none;
    text-align: center;
    border-radius: 5px;
}

.featured-products .product .btn:hover {
    background-color: #e67e22;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

footer .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

footer nav ul {
    list-style-type: none;
}

footer nav ul li {
    display: inline-block;
    margin-right: 20px;
}

footer nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}
