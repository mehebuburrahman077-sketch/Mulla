<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mulla Shop Store</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <div class="logo">
        <h1>Mulla Shop Store</h1>
        <p>mulla.smartbiz.in</p>
    </div>

    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">Categories</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Fashion That Defines You</h2>
    <p>Premium Clothing Collection for Men, Women & Kids</p>
    <a href="#" class="btn">Shop Now</a>
</section>

<section class="products">

    <div class="card">
        <img src="shirt.jpg" alt="Shirt">
        <h3>Casual Shirt</h3>
        <p>₹599</p>
    </div>

    <div class="card">
        <img src="jeans.jpg" alt="Jeans">
        <h3>Blue Jeans</h3>
        <p>₹999</p>
    </div>

    <div class="card">
        <img src="jacket.jpg" alt="Jacket">
        <h3>Winter Jacket</h3>
        <p>₹1499</p>
    </div>

</section>

<footer>
    <p>© 2026 Mulla Shop Store | mulla.smartbiz.in</p>
</footer>

</body>
</html>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f5f5f5;
}

header{
    background:#111;
    color:white;
    padding:15px 5%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 10px;
}

.hero{
    text-align:center;
    padding:80px 20px;
    background:#222;
    color:white;
}

.btn{
    display:inline-block;
    margin-top:15px;
    padding:12px 25px;
    background:#ffd700;
    color:black;
    text-decoration:none;
    border-radius:5px;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    padding:40px;
}

.card{
    background:white;
    border-radius:10px;
    overflow:hidden;
    text-align:center;
    box-shadow:0 2px 8px rgba(0,0,0,0.1);
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card h3{
    margin:10px 0;
}

.card p{
    color:green;
    margin-bottom:15px;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:15px;
}

@media(max-width:768px){
    header{
        flex-direction:column;
        text-align:center;
    }

    nav{
        margin-top:10px;
    }
}
