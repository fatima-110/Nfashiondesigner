# Nfashiondesigner
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About Us | N Fashion Designer</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>

<header class="navbar">
    <div class="logo">N Fashion Designer</div>

    <nav>
        <a href="index.html">Home</a>
        <a href="collection.html">Collection</a>
        <a href="about.html" class="active">About</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="page-banner">
<h1>About Us</h1>
<p>Premium Lawn Collection</p>
</section>

<section class="about-page">

<div class="about-image">
<img src="images/about.jpg" alt="">
</div>

<div class="about-content">

<h2>N Fashion Designer</h2>

<p>
We believe fashion should be elegant, comfortable and affordable.
Our collections are designed using premium lawn fabrics with modern
cuts that suit every occasion.
</p>

<p>
From everyday
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Collection</title>

<link rel="stylesheet" href="css/style.css">

</head>

<body>

<header class="navbar">

<div class="logo">
N Fashion Designer
</div>

<nav>
<a href="index.html">Home</a>
<a href="collection.html" class="active">Collection</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
</nav>

</header>

<section class="page-banner">
<h1>Our Collection</h1>
</section>

<section class="products">

<div class="product">

<img src="images/product1.jpg">

<h3>Plain Lawn Set</h3>

<p>Rs.3250</p>

<button>Order Now</button>

</div>

<div class="product">

<img src="images/product2.jpg">

<h3>Beige Lawn Set</h3>

<p>Rs.2950</p>

<button>Order Now</button>

</div>

<div class="product">

<img src="images/product3.jpg">

<h3>Black Lawn Set</h3>

<p>Rs.2950</p>

<button>Order Now</button>

</div>

<div class="product">

<img src="images/product4.jpg">

<h3>Rust Lawn Set</h3>

<p>Rs.3250</p>

<button>Order Now</button>

</div>

<div class="product">

<img src="images/product5.jpg">

<h3>Pink Lawn Set</h3>

<p>Rs.2990</p>

<button>Order Now</button>

</div>

<div class="product">

<img src="images/product6.jpg">

<h3>Blue Lawn Set</h3>

<p>Rs.3150</p>

<button>Order Now</button>

</div>

</section>

<footer>

<p>© 2025 N Fashion Designer</p>

</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Contact</title>

<link rel="stylesheet" href="css/style.css">

</head>

<body>

<header class="navbar">

<div class="logo">

N Fashion Designer

</div>

<nav>

<a href="index.html">Home</a>

<a href="collection.html">Collection</a>

<a href="about.html">About</a>

<a href="contact.html" class="active">Contact</a>

</nav>

</header>

<section class="page-banner">

<h1>Contact Us</h1>

</section>

<section class="contact-page">

<div class="contact-info">

<h2>Get In Touch</h2>

<p>📞 03172316912</p>

<p>📧 nfashiondesigner@gmail.com</p>

<p>📍 All Over Pakistan</p>

</div>

<form>

<input type="text" placeholder="Your Name" required>

<input type="email" placeholder="Email" required>

<input type="text" placeholder="Subject">

<textarea rows="6" placeholder="Message"></textarea>

<button type="submit">Send Message</button>

</form>

</section>

<footer>

<p>© 2025 N Fashion Designer</p>

</footer>

</body>

</html>

.page-banner{
background:#f7d8df;
padding:60px;
text-align:center;
}

.page-banner h1{
font-size:40px;
color:#444;
}

.about-page,
.contact-page{
display:flex;
gap:40px;
padding:60px 8%;
flex-wrap:wrap;
}

.about-image img{
width:100%;
max-width:450px;
border-radius:10px;
}

.about-content{
flex:1;
}

.features{
display:flex;
gap:20px;
margin-top:30px;
flex-wrap:wrap;
}

.feature{
background:#fff5f7;
padding:20px;
border-radius:8px;
flex:1;
min-width:180px;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
padding:60px 8%;
}

.product{
background:white;
padding:20px;
border-radius:10px;
text-align:center;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.product img{
width:100%;
border-radius:10px;
}

.product button{
background:#d86b83;
color:white;
border:none;
padding:12px 25px;
margin-top:15px;
cursor:pointer;
border-radius:5px;
}

.contact-page form{
flex:1;
display:flex;
flex-direction:column;
gap:15px;
}

.contact-page input,
.contact-page textarea{
padding:15px;
border:1px solid #ddd;
border-radius:5px;
}

.contact-page button{
background:#d86b83;
color:white;
padding:15px;
border:none;
cursor:pointer;
border-radius:5px;
}

footer{
background:#f7d8df;
padding:25px;
text-align:center;
margin-top:40px;
}
