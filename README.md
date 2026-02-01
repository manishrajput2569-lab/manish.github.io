<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> Booking Flow </title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#f4f4f4;
}
header{
    background:#0a6cff;
    color:#fff;
    padding:20px;
    text-align:center;
}
.hero{
    background:url("https://images.unsplash.com/photo-1507525428034-b723cf961d3e") no-repeat center;
    background-size:cover;
    height:320px;
    color:#fff;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:32px;
    font-weight:bold;
}
.container{
    width:90%;
    margin:auto;
}
.section{
    padding:40px 0;
}
.packages{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}
.card{
    background:#fff;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
    text-align:center;
}
.card img{
    width:100%;
    height:180px;
    object-fit:cover;
}
.card h3{
    padding:10px;
}
.card p{
    padding:0 10px;
}
.btn{
    display:inline-block;
    margin:15px;
    padding:10px 22px;
    background:#0a6cff;
    color:#fff;
    text-decoration:none;
    border-radius:5px;
}
.quote-box{
    background:#fff;
    padding:40px 20px;
    text-align:center;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
    margin:40px auto;
    max-width:700px;
}
footer{
    background:#222;
    color:#fff;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
<h1>Booking Flow</h1>
<p> <h3>Data Network </p>
<p>Smart leads. Drive growth</p>
</header>

<div class="hero">
Explore The World With Us
</div>

<div class="container">

<div class="section">
<h2>Our Packages</h2>

<div class="packages">

<div class="card">
<img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470">
<h3>Manali Tour</h3>
<p>3 Nights / 4 Days ₹9,999</p>
<a class="btn" href="https://docs.google.com/forms/d/e/1FAIpQLSdcGv3HUc7khTLwxiXDWCVAHI_mRX7qpC8p3yNBAgKrwx1pcg/viewform" target="_blank">Book Now</a>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee">
<h3>Goa Trip</h3>
<p>4 Nights / 5 Days ₹13,999</p>
<a class="btn" href="https://docs.google.com/forms/d/e/1FAIpQLSdcGv3HUc7khTLwxiXDWCVAHI_mRX7qpC8p3yNBAgKrwx1pcg/viewform" target="_blank">Book Now</a>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1505761671935-60b3a7427bad">
<h3>Dubai Holiday</h3>
<p>5 Nights / 6 Days ₹49,999</p>
<a class="btn" href="https://docs.google.com/forms/d/e/1FAIpQLSdcGv3HUc7khTLwxiXDWCVAHI_mRX7qpC8p3yNBAgKrwx1pcg/viewform" target="_blank">Book Now</a>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1524492412937-b28074a5d7da">
<h3>Jaipur Tour</h3>
<p>2 Nights / 3 Days ₹7,499</p>
<a class="btn" href="https://docs.google.com/forms/d/e/1FAIpQLSdcGv3HUc7khTLwxiXDWCVAHI_mRX7qpC8p3yNBAgKrwx1pcg/viewform" target="_blank">Book Now</a>
</div>

</div>
</div>

<div class="section">
<h2>Local & Weekend Tours</h2>

<div class="packages">

<div class="card">
<img src="https://images.unsplash.com/photo-1521295121783-8a321d551ad2">
<h3>Shimla Local</h3>
<p>1 Day Trip ₹2,199</p>
<a class="btn" href="https://docs.google.com/forms/d/e/1FAIpQLSdcGv3HUc7khTLwxiXDWCVAHI_mRX7qpC8p3yNBAgKrwx1pcg/viewform" target="_blank">Book Now</a>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1548013146-72479768bada">
<h3>Kasol & Manikaran</h3>
<p>2 Days / 1 Night ₹4,999</p>
<a class="btn" href="https://docs.google.com/forms/d/e/1FAIpQLSdcGv3HUc7khTLwxiXDWCVAHI_mRX7qpC8p3yNBAgKrwx1pcg/viewform" target="_blank">Book Now</a>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1598279214961-7ac94a8f87ae">
<h3>Dharamshala</h3>
<p>2 Days / 1 Night ₹4,799</p>
<a class="btn" href="https://docs.google.com/forms/d/e/1FAIpQLSdcGv3HUc7khTLwxiXDWCVAHI_mRX7qpC8p3yNBAgKrwx1pcg/viewform" target="_blank">Book Now</a>
</div>

</div>
</div>

<div class="quote-box">
<h2 style="color:#0a6cff;">Plan Your Dream Trip 🌍</h2>
<p>Share your travel details and get the best customized deals.</p>
<a href="https://docs.google.com/forms/d/e/1FAIpQLSdcGv3HUc7khTLwxiXDWCVAHI_mRX7qpC8p3yNBAgKrwx1pcg/viewform" target="_blank">Get Your Travel Quote</a>
</div>

</div>

<footer>
<h3>Contact Us</h3>
<p>Phone: +91 7876338389</p>
<p>Email:manishrajput2569@gmail.com</p>
<p>Address: Himachal Pradesh, India</p>
<p>Booking Flow</p>
</footer>

</body>
</html>

