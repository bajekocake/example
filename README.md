<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bajeko Cake | Premium Cake Shop in Kathmandu | Order Online</title>
  
  
  <link rel="preload" as="image" href="hero.webp">
  <link rel="icon" href="logo.png" type="image/png">
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

  <!-- Primary Meta Tags -->
  <meta name="description" content="Bajeko Cake in Kathmandu offers premium birthday, wedding, and eggless cakes. Order online for fast delivery and celebrate every occasion with delicious cakes.">
  <meta name="keywords" content="cake shop Kathmandu, birthday cake Nepal, baby girl cake,baby boy cake, kid cake, anniversary cake, cake in lalitpur, cake in bhaktapur, wedding cake Kathmandu, chocolate cake kathmandu, cake in bhaktapur, free delivery in kathmandu,eggless cake Nepal, Bajeko Cake">
  <meta name="author" content="Bajeko Cake">
  <meta name="robots" content="index, follow">

  <!-- Geo Tags for Local SEO -->
  <meta name="geo.region" content="NP-BAG">
  <meta name="geo.placename" content="Kathmandu">
  <meta name="geo.position" content="27.6693;85.3302">
  <meta name="ICBM" content="27.6693, 85.3302">

  <!-- Open Graph / Social Sharing -->
  <meta property="og:title" content="Bajeko Cake - Premium Cakes in Kathmandu">
  <meta property="og:description" content="Order delicious cakes for birthdays, weddings, and special occasions. Fast delivery in Kathmandu.">
  <meta property="og:image" content="https://i.postimg.cc/9fsnf4MF/PXL-20221023-133551308-PORTRAIT.webp">
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://bajekocake.com.np">

  <!-- Twitter Card -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Bajeko Cake - Premium Cakes in Kathmandu">
  <meta name="twitter:description" content="Order delicious cakes for birthdays, weddings, and special occasions. Fast delivery in Kathmandu.">
  <meta name="twitter:image" content="https://i.postimg.cc/9fsnf4MF/PXL-20221023-133551308-PORTRAIT.webp">

  <!-- Canonical -->
  <link rel="canonical" href="https://bajekocake.com.np">

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

 

  

  <!-- Styles -->
  <style>
    /* RESET */
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Poppins',sans-serif;
background:#0f0f0f;
color:white;
overflow-x:hidden;
}
/* 🔥 PREMIUM GRADIENT BACKGROUND */
body::before{
content:"";
position:fixed;
width:100%;
height:100%;
background: radial-gradient(circle at 20% 20%, rgba(255,180,120,0.15), transparent),
            radial-gradient(circle at 80% 80%, rgba(255,120,180,0.12), transparent);
z-index:-1;
}

   /* HEADER */
header{
text-align:center;
padding:80px 20px;
}

header h1{
font-family:'Playfair Display',serif;
font-size:64px;
letter-spacing:2px;
background: linear-gradient(90deg,#ffd700,#fff,#ffd700);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

header p{
margin-top:10px;
opacity:0.7;
}
    

    /* NAV */
nav{
display:flex;
justify-content:center;
gap:40px;
padding:20px;
backdrop-filter:blur(10px);
background:rgba(255,255,255,0.05);
position:sticky;
top:0;
z-index:999;
}

nav a{
color:white;
text-decoration:none;
font-weight:500;
transition:0.3s;
}

nav a:hover{
color:#ffd700;
}

    /* Slider */
     .slider::after {
  content: "";
  position: absolute;
  width: 100%;
  height: 400px;
  background: linear-gradient(to bottom, rgba(0,0,0,0.2), #0f0f0f);
  top: 0;
} 
 

.slides {
  display: flex;
  animation: slide 8s infinite;
}

.slides img {
  width: 100%;
  height: 400px;
  object-fit: cover;
}

@keyframes slide {
  0%,20% { transform: translateX(0); }
  25%,45% { transform: translateX(-100%); }
  50%,70% { transform: translateX(-200%); }
  75%,95% { transform: translateX(-300%); }
  100% { transform: translateX(0); }
}
   
   
   
   

    /* Sections */
    section { padding:40px 20px; }

    /* Featured & Trending */
    .featured { text-align:center; }
    .featured-grid, .cake-container { display:grid; gap:25px; grid-template-columns: repeat(auto-fit,minmax(220px,1fr)); margin-top:20px; justify-items:center; }
    .featured-card, .cake-card { background:white; border-radius:12px; padding:15px; box-shadow:0 4px 10px rgba(0,0,0,0.1); display:flex; flex-direction:column; align-items:center; transition:0.3s; }
    .featured-card:hover, .cake-card:hover { transform:translateY(-5px); }
    .featured-card img, .cake-card img { width:100%; height:100%; object-fit:cover; border-radius:10px; margin-bottom:10px; }
    
    .featured-card button,
    .cake-card button,
    .book-btn,
    .product-card button {
      background: linear-gradient(135deg, #e98e3a, #f7b16a);
      color: white;
      border: none;
      padding: 10px 16px;
      border-radius: 20px;
      cursor: pointer;
      font-weight: bold;
      width: 100%;
      margin-top: 10px;
      transition: 0.3s;
      font-family: 'Poppins', sans-serif;
    }

    .featured-card button:hover,
    .cake-card button:hover,
    .book-btn:hover,
    .product-card button:hover {
      background: linear-gradient(135deg, #f7b16a, #ffd700);
      transform: scale(1.05);
      color: #000;
    }
    
    
    
    .featured h2 { font-family: 'Dancing Script', cursive; font-size:48px; color:#e98e3a; letter-spacing:2px; text-shadow:2px 2px 8px rgba(0,0,0,0.15); }

    /* Product Filter Buttons */
    .category-buttons { display:flex; justify-content:center; gap:15px; flex-wrap:wrap; margin-bottom:50px; }
    .category-buttons button { padding:10px 16px; border:none; background:#e98e3a; color:white; border-radius:35px; cursor:pointer; font-size:13px; }
    /* PRODUCTS GRID */
.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 220px));
  justify-content: center;
  gap: 20px;
}


.featured-card, .cake-card {
  background: rgba(255,255,255,0.05);
  backdrop-filter: blur(20px);
  border-radius: 20px;
  padding: 15px;
  border: 1px solid rgba(255,255,255,0.08);
  box-shadow: 0 20px 60px rgba(0,0,0,0.4);
  transition: 0.4s ease;
}

.featured-card:hover, .cake-card:hover {
  transform: translateY(-10px) scale(1.03);
  box-shadow: 0 30px 80px rgba(255,215,0,0.2);
}
/* PRODUCT CARD */
.product-card {
      text-align: center;
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(20px);
      border-radius: 20px;
      padding: 15px;
      border: 1px solid rgba(255,255,255,0.08);
      box-shadow: 0 20px 60px rgba(0,0,0,0.4);
      transition: 0.4s ease;
      /* FIX #10: Removed float animation from all product cards — only applied to featured hero cards now */
    }

/* PRODUCT IMAGE */
.product-card img {
  width: 100%;
  aspect-ratio: 1/1;
  object-fit: cover;
  border-radius: 10px;
  transition: 0.3s;
}

/* HOVER EFFECT */
.product-card img:hover {
  transform: scale(1.06);
}

/* TITLE */
.product-card h3 {
  margin-top: 10px;
  font-size: 16px;
}

/* DESCRIPTION */
.product-card p {
  font-size: 14px;
  color: #555;
  margin: 5px 0;
}


/* Button */
product-card button {
      background: linear-gradient(135deg, #e98e3a, #f7b16a);
      color: white;
      border: none;
      padding: 10px 16px;
      border-radius: 20px;
      cursor: pointer;
      font-weight: bold;
      width: 100%;
      margin-top: 10px;
      transition: 0.3s;
      font-family: 'Poppins', sans-serif;
    }
/* BUTTON */
button {
  background: linear-gradient(135deg,#ffd700,#ffb347);
  color: black;
  font-weight: 600;
}

button:hover {
  background: white;
  color: black;
}







    /* Gallery */
    .gallery-section{ display:none; text-align:center; }
    .gallery{ display:grid; grid-template-columns:repeat(auto-fit,minmax(200px,1fr)); gap:20px; }
    .gallery img{ width:100%; height:100%; object-fit:cover; border-radius:10px; cursor:pointer; transition:transform 0.3s; }
    .gallery img:hover{ transform:scale(1.1); }
    
    
    
    /* =========================
   ABOUT US PREMIUM SECTION
========================= */

.about-us{
position:relative;
padding:120px 8%;
overflow:hidden;
}

.about-overlay{
position:absolute;
inset:0;

background:
radial-gradient(circle at top left,
rgba(255,215,0,0.08),
transparent 35%),

radial-gradient(circle at bottom right,
rgba(255,180,120,0.08),
transparent 35%);
}

.about-container{
position:relative;
z-index:2;

display:grid;
grid-template-columns:1fr 1fr;
gap:80px;
align-items:center;
}

.about-tag{
display:inline-block;

padding:10px 18px;

border-radius:40px;

background:rgba(255,255,255,0.08);

border:1px solid rgba(255,255,255,0.1);

font-size:13px;
letter-spacing:2px;
margin-bottom:25px;

color:#ffd700;
}

.about-left h2{
font-family:'Playfair Display',serif;
font-size:64px;
line-height:1.1;
margin-bottom:30px;

background:linear-gradient(
90deg,
#fff,
#ffd700,
#fff
);

-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.about-description{
font-size:17px;
line-height:1.9;
opacity:0.8;
margin-bottom:20px;
max-width:650px;
}

.about-stats{
display:flex;
gap:25px;
margin-top:40px;
flex-wrap:wrap;
}

.stat-box{
background:rgba(255,255,255,0.05);

backdrop-filter:blur(18px);

padding:25px;

border-radius:24px;

min-width:150px;

border:1px solid rgba(255,255,255,0.08);

box-shadow:
0 15px 40px rgba(0,0,0,0.35);

transition:0.4s ease;
}

.stat-box:hover{
transform:translateY(-8px);
}

.stat-box h3{
font-size:38px;
color:#ffd700;
margin-bottom:8px;
}

.stat-box p{
opacity:0.7;
font-size:14px;
}

.about-btn{
display:inline-block;

margin-top:40px;

padding:16px 30px;

border-radius:50px;

background:linear-gradient(
135deg,
#ffd700,
#ffb347
);

color:black;
font-weight:700;
text-decoration:none;

transition:0.4s ease;

box-shadow:
0 15px 40px rgba(255,215,0,0.2);
}

.about-btn:hover{
transform:translateY(-5px) scale(1.03);

box-shadow:
0 25px 60px rgba(255,215,0,0.35);
}

/* RIGHT SIDE */

.about-right{
  position:relative;
  height:auto;
  display:flex;
  flex-wrap:wrap;
  gap:15px;
  justify-content:center;
}

.about-image{
  position:relative;
  width:100%;
  max-width:260px;
  height:260px;
}

.about-image img{
width:100%;
height:100%;
object-fit:cover;

transition:0.6s ease;
}

.about-image:hover img{
transform:scale(1.08);
}

.about-image:hover{
transform:translateY(-10px);
}

.image-1{
width:300px;
height:420px;
top:0;
left:0;
}

.image-2{
width:260px;
height:340px;
top:80px;
right:0;
}

.image-3{
width:340px;
height:240px;
bottom:0;
left:120px;
}




#upcoming-event {
  display: none;
}

/* MOBILE */

@media(max-width:768px){

.about-container{
grid-template-columns:1fr;
}

.about-left h2{
font-size:32px;
}

.about-right{
height:550px;
margin-top:40px;
}

.image-1{
width:220px;
height:300px;
}

.image-2{
width:190px;
height:250px;
}

.image-3{
width:250px;
height:180px;
left:60px;
}

.about-stats{
justify-content:center;
}

}
    
    
    
    
    
    
    
    

    /* Lightbox */
    .lightbox {
  display: none;
  position: fixed;
  z-index: 1000;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0,0,0,0.95);
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

/* Image */
.lightbox img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 10px;
  transition: transform 0.3s ease;
  cursor: grab;
}

/* FLOAT ANIMATION */
@keyframes float {
      0%   { transform: translateY(0); }
      50%  { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }

    .featured-card:first-child {
      animation: float 6s ease-in-out infinite;
    }

/* Close button */
.close {
  position: absolute;
  top: 20px;
  right: 30px;
  font-size: 40px;
  color: white;
  cursor: pointer;
}

/* Navigation arrows */
.nav {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  font-size: 40px;
  color: white;
  cursor: pointer;
  padding: 10px;
  user-select: none;
}

.prev { left: 20px; }
.next { right: 20px; }

 /* Upcoming Event Section */
.upcoming-event {
    background: #fff3f6;
    text-align: center;
    padding: 40px 20px;
    border-radius: 15px;
    margin: 40px auto;
    
}

.event-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 25px;
  margin-top: 30px;
}

.event-box {
  background: white;
  padding: 25px;
  border-radius: 15px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  transition: 0.3s;
}

.event-box:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 40px rgba(233,142,58,0.25);
}

.event-box h3 {
  font-size: 22px;
  margin-bottom: 10px;
  color: #e98e3a;
}

/* 🎉 FESTIVAL BACKGROUND EFFECT */
.upcoming-event {
  position: relative;
  overflow: hidden;
}

/* Floating Rakhi Threads */
.rakhi {
  position: absolute;
  width: 50px;
  opacity: 0.8;
  animation: floatRakhi linear infinite;
}

@keyframes floatRakhi {
  0% {
    transform: translateY(100vh) rotate(0deg);
    opacity: 0;
  }
  20% { opacity: 1; }
  100% {
    transform: translateY(-10vh) rotate(360deg);
    opacity: 0;
  }
}

/* Sparkle particles */
.sparkle {
  position: absolute;
  width: 6px;
  height: 6px;
  background: gold;
  border-radius: 50%;
  animation: sparkleAnim 3s infinite ease-in-out;
}

@keyframes sparkleAnim {
  0%,100% { opacity: 0; transform: scale(0.5); }
  50% { opacity: 1; transform: scale(1.5); }
}

/* Flashing Event Title */
.flash-title {
    font-size: 2.5rem;
    font-weight: bold;
    color: #e4405f;
    animation: flash 1s infinite;
}

@keyframes flash {
    0%, 50%, 100% { opacity: 1; }
    25%, 75% { opacity: 0.2; }
}



* {
  -webkit-tap-highlight-color: transparent;
}

button, a {
  touch-action: manipulation;
}

/* Flip Countdown */
.flip-countdown {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin: 20px 0;
}

.time-box {
    background: #222;
    color: white;
    padding: 15px;
    border-radius: 10px;
    width: 100px;
    text-align: center;
}

.time-box span {
    font-size: 30px;
    font-weight: bold;
    display: block;
}

.flip {
    animation: flip 0.5s;
}

@keyframes flip {
    0% { transform: rotateX(0); }
    50% { transform: rotateX(90deg); }
    100% { transform: rotateX(0); }
}


/* WhatsApp Order Button */
.order-btn {
    display: inline-block;
    background: #25D366;
    color: white;
    padding: 12px 20px;
    border-radius: 25px;
    text-decoration: none;
    font-weight: bold;
    margin-top: 15px;
    transition: 0.3s;
}




/* =========================
CUSTOMER HIGHLIGHTS
========================= */

.customer-highlights{
margin-top:70px;
}

.highlight-title{
margin-bottom:35px;
}

.highlight-title span{
display:inline-block;
padding:10px 18px;
border-radius:30px;
background:rgba(255,255,255,0.06);
border:1px solid rgba(255,255,255,0.08);
color:#ffd700;
font-size:13px;
letter-spacing:1px;
margin-bottom:18px;
}

.highlight-title h3{
font-size:42px;
font-family:'Playfair Display',serif;
background:linear-gradient(90deg,#fff,#ffd700,#fff);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.review-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:25px;
}

.review-card{
background:rgba(255,255,255,0.05);
backdrop-filter:blur(18px);
border:1px solid rgba(255,255,255,0.08);
border-radius:28px;
padding:30px;
transition:0.4s ease;
box-shadow:0 20px 50px rgba(0,0,0,0.35);
position:relative;
overflow:hidden;
}

.review-card:hover{
transform:translateY(-10px);
box-shadow:0 30px 70px rgba(255,215,0,0.15);
}

.review-card::before{
content:"";
position:absolute;
top:-80px;
right:-80px;
width:180px;
height:180px;
background:radial-gradient(circle,
rgba(255,215,0,0.15),
transparent 70%);
}

.review-stars{
font-size:22px;
color:#ffd700;
margin-bottom:18px;
}

.review-text{
font-size:15px;
line-height:1.9;
opacity:0.85;
margin-bottom:25px;
}

.review-user{
display:flex;
align-items:center;
gap:15px;
}

.review-user img{
width:55px;
height:55px;
border-radius:50%;
object-fit:cover;
border:2px solid rgba(255,255,255,0.1);
}

.review-user h4{
font-size:16px;
margin-bottom:3px;
}

.review-user span{
font-size:13px;
opacity:0.65;
}

.featured-review{
border:1px solid rgba(255,215,0,0.3);
transform:scale(1.03);
}

.featured-review:hover{
transform:translateY(-10px) scale(1.04);
}

@media(max-width:768px){

.highlight-title h3{
font-size:32px;
}

.review-card{
padding:24px;
}

}






    /* WhatsApp Floating */
    .whatsapp-icon { position:fixed; bottom:20px; right:20px; background:#25D366; color:white; font-size:28px; padding:15px; border-radius:50%; text-decoration:none; box-shadow:0 4px 10px rgba(0,0,0,0.3); }
    .whatsapp-icon:hover { background:#1ebe5d; }

    .footer {
  background: #5a3e1b;
  color: white;
  padding: 40px 20px;
}

.footer-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
  align-items: center;
  text-align: center;
}

.footer-box h3 {
  margin-bottom: 10px;
}

.footer-logo {
  width: 80px;
  margin-bottom: 10px;
}

.slogan {
  font-family: 'Dancing Script', cursive;
  font-size: 24px;
  font-weight: 700;
  letter-spacing: 1.2px;

  background: linear-gradient(90deg, #d4af37, #ffd700, #fff1a8, #c5a100);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;

  text-shadow: 0 2px 6px rgba(0,0,0,0.3);
}

.footer-social {
  margin-top: 10px;
}

.footer-social {
  margin-top: 10px;
  display: flex;
  justify-content: center;
  gap: 15px;
}

.footer-social a {
  width: 35px;
  height: 35px;
  border-radius: 30%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 18px;
  transition: 0.3s ease;
}

/* Messenger Floating Button */
.messenger-icon {
position: fixed;
bottom: 100px;
right: 20px;
background: linear-gradient(135deg,#0084ff,#00c6ff);
color: white;
font-size: 26px;
padding: 15px;
border-radius: 50%;
text-decoration: none;
box-shadow: 0 4px 12px rgba(0,0,0,0.3);
transition: 0.3s;
z-index: 999;
}

.messenger-icon:hover {
transform: scale(1.1);
box-shadow: 0 6px 18px rgba(0,0,0,0.4);
}

/* Facebook Modern */
.footer-social .facebook {
  background: linear-gradient(135deg, #1877f2, #4e9cff);
  box-shadow: 0 4px 12px rgba(24,119,242,0.4);
}

/* Instagram Modern */
.footer-social .instagram {
  background: linear-gradient(135deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
  box-shadow: 0 4px 12px rgba(225,48,108,0.4);
}

/* Hover Effect */
.footer-social a:hover {
  transform: translateY(-4px) scale(1.08);
  box-shadow: 0 8px 20px rgba(0,0,0,0.3);
}


.copyright {
  text-align: center;
  margin-top: 30px;
  font-size: 14px;
  opacity: 0.8;
}

nav a {
  cursor: pointer;
}



/*hero  */ 
.hero{
text-align:center;
padding:60px 20px;
}

.hero h2{
font-family:'Playfair Display',serif;
font-size:42px;
margin-bottom:10px;
}

.hero p{
opacity:0.7;
margin-bottom:20px;
}



html, body {
  overflow-x: hidden;
  width: 100%;
}
img {
  max-width: 100%;
  height: auto;
}

    /* Map */
    .map-container { max-width:300px; margin:auto; border-radius:5px; overflow:hidden; box-shadow:0 5px 5px rgba(0,0,0,0.2); text-align:center; }
    
    
    /* FIX #12: Mobile nav — cleaner 3-column grid instead of awkward 2+2+1 */
    @media (max-width: 768px) {
      header h1 { font-size: 50px; }
      .hero h2 { font-size: 28px; }

      nav {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 8px;
        padding: 12px;
      }

      nav a {
        text-align: center;
        font-size: 13px;
        padding: 10px 6px;
        border-radius: 12px;
        background: rgba(255,255,255,0.06);
        border: 1px solid rgba(255,255,255,0.08);
      }

      .about-container { grid-template-columns: 1fr; }
      .about-left h2 { font-size: 32px; }
      .about-right { margin-top: 40px; }
      .highlight-title h3 { font-size: 32px; }
      .review-card { padding: 24px; }
      .footer-grid { grid-template-columns: 1fr; }
    }
    
    
    
  </style>
</head>
<body>

<!-- Header -->
<header>
  <h1>Bajeko Cake</h1>
  <h2 style="text-align:center; font-size:20px; color:#FFD700;">
Best Cake Shop in Kathmandu | Order Birthday, Wedding & Custom Cakes 🎂
</h2>
    
  <p>
  Order Online🎂</p>
</header>

<!-- Navigation -->
<nav>
  <a href="#" onclick="showHome(); return false;">Home</a>
<a href="#" onclick="showProducts(); return false;">Products</a>
<a href="#" onclick="showGallery(); return false;">Gallery</a>
<a href="#" onclick="showContact(); return false;">Contact</a>
  <a href="#" onclick="showAbout(); return false;">About Us</a>
</nav>

<section class="hero">
  <h2>Luxury Cakes Crafted for Your Moments</h2>
  <p>Handmade in Kathmandu with premium ingredients</p>
  
  </section>

<!-- Home Section -->
<section id="home-section">
  <!-- Slider -->
  <div class="slider">
    <div class="slides">
      <img src="https://i.postimg.cc/MGwg9VBQ/Gemini-Generated-Image-a28fa2a28fa2a28f-2.jpg">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/IMG_20250726_114354841.jpg">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/images%20(7).jpg">
      <img src="https://i.postimg.cc/s2bN2BX3/unnamed.webp">
      <img src="https://i.postimg.cc/9fsnf4MF/PXL_20221023_133551308_PORTRAIT.webp">
      <img src="https://i.postimg.cc/MGwg9VBQ/Gemini-Generated-Image-a28fa2a28fa2a28f-2.jpg">
      <img src="https://i.postimg.cc/7PmQxsH3/1776662821347-3.jpg">
       <img src="https://i.postimg.cc/GpGBK3HV/PXL-20251219-065311679-PORTRAIT-2-(1).jpg">
        <img src="https://i.postimg.cc/W3gZ4zxM/1774960855220-2.jpg">
         <img src="https://i.postimg.cc/gjnmJQTs/1777454965754-3.jpg">
     
    </div>
  </div>

  <!-- Featured Cakes -->
  <section class="featured">
    <h2>Featured Cakes</h2>
    <div class="featured-grid">
      <div class="featured-card">
        <img src="https://i.postimg.cc/pdB31trP/5065b81874cef6dea46d7ba330d6a520.jpg"loading="lazy" onclick="openLightbox(this)">
        <button onclick="orderWhatsApp('Cake')">Order Now</button>
      </div>
      <div class="featured-card">
        <img src="https://i.postimg.cc/RhNvFJP2/35cc0cfadc752e6c264a276b57c3b489.jpg"loading="lazy" onclick="openLightbox(this)">
        <button onclick="orderWhatsApp('Cake')">Order Now</button>
      </div>
      <div class="featured-card">
        <img src="https://i.postimg.cc/N0ksPc9x/eee9731959bc2bbf48e056efbe19a465.jpg"loading="lazy" onclick="openLightbox(this)">
        <button onclick="orderWhatsApp('Cake')">Order Now</button>
      </div>
      <div class="featured-card">
        <img src="https://i.postimg.cc/1519PXGG/280cfa49bda6d5367dbc5395527e8209.jpg"loading="lazy" onclick="openLightbox(this)">
        <button onclick="orderWhatsApp('Cake')">Order Now</button>
      </div>
    </div>
  </section>
  
  <section style="text-align:center; padding:40px;">
<h2>Why Choose Us?</h2>
<p>⭐⭐⭐⭐⭐500+ Happy Customers</p>
<p>⭐⭐⭐⭐⭐ Same Day Delivery</p>
<p>⭐⭐⭐⭐⭐Premium Quality Ingredients</p>
</section>

  <!-- Trending Cakes -->
  <section class="featured">
    <h1>🎂 Trending Cakes 🎂</h1>
    <div class="cake-container">
      <div class="cake-card">
        <img src="https://i.postimg.cc/x8hYBHZd/1757957251368_3.jpg"loading="lazy" onclick="openLightbox(this)" alt="Butterfly Cake">
        <h3>Butterfly Cake</h3>
        <button onclick="orderWhatsApp('Butterfly Cake')">Order Now</button>
      </div>
      <div class="cake-card">
        <img src="https://i.postimg.cc/J0vmSJFK/1773807815441_3.jpg"loading="lazy" onclick="openLightbox(this)" alt="Calender cake">
        <h3>Calender Cake</h3>
        <button onclick="orderWhatsApp('Calender Cake')">Order Now</button>
      </div>
      <div class="cake-card">
        <img src="https://i.postimg.cc/ZRXRmWm5/PXL_20260213_105958536_PORTRAIT_2.jpg"loading="lazy" onclick="openLightbox(this)" alt="Farewell Cake">
        <h3>Farewell Cake</h3>
        <button onclick="orderWhatsApp('Farewell Cake')">Order Now</button>
      </div>
       <div class="cake-card">
        <img src="https://i.postimg.cc/T2z8ptZ8/1774106792829_2.jpg"loading="lazy"onclick="openLightbox(this)" alt="Just Engaged Cake">
        <h3>Just Engaged Cake</h3>
        <button onclick="orderWhatsApp('Just Engaged Cake')">Order Now</button>
      </div>
      
      <div class="cake-card">
        <img src="https://i.postimg.cc/gjnmJQTs/1777454965754-3.jpg"loading="lazy"onclick="openLightbox(this)" alt="CoCa Melon Cake">
        <h3>CoCa Melon Cake</h3>
        <button onclick="orderWhatsApp('CoCa Melon Cake')">Order Now</button>
      </div>
      
        <div class="cake-card">
        <img src="https://i.postimg.cc/ZY6nB1ny/1774961100650_2.jpg"loading="lazy" onclick="openLightbox(this)" alt="Combo:Bento Cake + Bouquet">
        <h3>Combo:Bento Cake + Bouquet</h3>
        <button onclick="orderWhatsApp('Combo:Bento Cake + Bouquet')">Order Now</button>
      </div>
      
      <div class="cake-card">
        <img src="https://i.postimg.cc/QMtGsW95/1774961328614-2.jpg"loading="lazy" onclick="openLightbox(this)" alt="Gym Freak Cake">
        <h3>Gym Freak Cake</h3>
        <button onclick="orderWhatsApp('Gym Freak Cake')">Order Now</button>
      </div>
      
      <div class="cake-card">
        <img src="https://i.postimg.cc/wv3cjDKz/1775308767579-2.jpg"loading="lazy" onclick="openLightbox(this)" alt="Whiskey Chocolate Delight">
        <h3>Whiskey Chocolate Delight</h3>
        <button onclick="orderWhatsApp('Whiskey Chocolate Delight')">Order Now</button>
      </div>
      
      
      <div class="cake-card">
        <img src="https://i.postimg.cc/Y98gP7m0/1775649829589-3.jpg"loading="lazy" onclick="openLightbox(this)" alt="Magical Unicorn Cake">
        <h3>Magical Unicorn Cake</h3>
        <button onclick="orderWhatsApp('Magical Unicorn Cake')">Order Now</button>
      </div>
      
       <div class="cake-card">
        <img src="https://i.postimg.cc/QdHsZpY9/1775287022843-2-(1).jpg"loading="lazy" onclick="openLightbox(this)" alt="Charming Princess Cake">
        <h3>Charming Princess Cake</h3>
        <button onclick="orderWhatsApp('Charming Princess Cake')">Order Now</button>
      </div>
      
        <div class="cake-card">
        <img src="https://i.postimg.cc/7PmQxsH3/1776662821347-3.jpg"loading="lazy" onclick="openLightbox(this)" alt="Elsa Frozen Cake">
        <h3>Elsa Frozen Cake</h3>
        <button onclick="orderWhatsApp('Elsa Frozen Cake')">Order Now</button>
      </div>
     
     
      
    </div>
  </section>
</section>

<!-- Products Section -->
<section id="products" style="display:none">
  <h2>Shop by Category</h2>
  <div class="category-buttons">
    <button onclick="filterCategory('all')">All</button>
    <button onclick="filterCategory('quick')">Quick Cake</button>
    <button onclick="filterCategory('eggless')">Eggless Cake</button>
    <button onclick="filterCategory('wedding')">Wedding Cake</button>
    <button onclick="filterCategory('cheese')">Cheese Cake</button>
    <button onclick="filterCategory('baby-Girl')">Baby Girl Cake</button>
    <button onclick="filterCategory('baby-shower')">Baby Shower Cake</button>
  </div>

  <div class="products" id="product-list">
    <div class="product-card" data-category="quick">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/95a33ceb554a695b8f016d2a73526fc3.jpg"loading="lazy" onclick="openLightbox(this)">
      <h3>Quick Chocolate Cake</h3>
      <p>Fast-picked, rich & moist.</p>
      <button class="book-btn" onclick="window.open('https://wa.me/9779867221301?text=I want to order Chocolate cake')">Book Order</button>
    </div>

    <div class="product-card" data-category="eggless">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/Red-Velvet-Birthday-Cake-scaled.jpeg"loading="lazy"onclick="openLightbox(this)">
      <h3>Eggless Red Velvet</h3>
      <p>Soft, smooth & completely egg-free.</p>
      <button class="book-btn" onclick="window.open('https://wa.me/9779867221301?text=I want to order RedVelvet cake')">Book Order</button>
    </div>

    <div class="product-card" data-category="wedding">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/royal%20cake.jpg"loading="lazy"onclick="openLightbox(this)">
      <h3>Royal Wedding Cake</h3>
      <p>Elegant multi-tier handcrafted design.</p>
      <button class="book-btn" onclick="window.open('https://wa.me/9779867221301?text=I want to order Wedding Cake')">Book Order</button>
    </div>

    <div class="product-card" data-category="cheese">
      <img src="https://uploads.onecompiler.io/4454cur5q/4454cuf35/1200x1200px_Blueberry_Cheesecake.png"loading="lazy"onclick="openLightbox(this)">
      <h3>Classic Cheesecake</h3>
      <p>Creamy, smooth & premium cheese blend.</p>
      <button class="book-btn" onclick="window.open('https://wa.me/9779867221301?text=I want to order Classic Cheesecake')">Book Order</button>
    </div>

    <div class="product-card" data-category="baby-Girl">
      <img src="https://uploads.onecompiler.io/4454cur5q/44dkqaxax/PXL_20250119_074100280.PORTRAIT~2.jpg?auto=format&fit=crop&w=800&q=80">
      <h3>Baby Girl Cake</h3>
      <p>Enriched in design.</p>
      <button class="book-btn" onclick="window.open('https://wa.me/9779867221301?text=I want to order Barbie Cake')">Book Order</button>
    </div>

    <div class="product-card" data-category="baby-shower">
      <img src="https://uploads.onecompiler.io/4454cur5q/44ggazag5/PXL_20251018_072821655%20(1).jpg?auto=format&fit=crop&w=800&q=80">
      <h3>Baby Shower Cake</h3>
      <p>Twinkle, twinkle little star, can't wait to see how cute you are.</p>
      <button class="book-btn" onclick="window.open('https://wa.me/9779867221301?text=I want to order Cake')">Book Order</button>
    </div>
  </div>
</section>

<!-- Gallery Section -->
<section class="gallery-section" id="gallery-section">
  <h2>Cake Gallery</h2>
  <div class="category-buttons">
    <button onclick="filterGallery('all')">All</button>
    <button onclick="filterGallery('kid')">Kid Cake</button>
    <button onclick="filterGallery('elegant')">Elegant Cake</button>
    <button onclick="filterGallery('wedding')">Wedding Cake</button>
    <button onclick="filterGallery('football')">Football Cake</button>
  </div>
  <div class="gallery" id="gallery-container"></div>
</section>











<!-- Lightbox -->
<div class="lightbox" id="lightbox">
  <span class="close" onclick="closeLightbox()">&times;</span>

  <img id="lightbox-img">

  <!-- Navigation -->
  <div class="nav prev" onclick="changeSlide(-1)">❮</div>
  <div class="nav next" onclick="changeSlide(1)">❯</div>
</div>

<!-- Upcoming Event -->
<section class="upcoming-event" id="upcoming-event">
  <h2 class="flash-title">🎉 Upcoming Celebrations 🎉</h2>

  <div class="event-grid">

    

    <!-- Rakshya Bandhan -->
    <div class="event-box">
      <h3>🪢 Rakshya Bandhan</h3>
      <p>Celebrate sibling love with a special cake 💝</p>

      <div class="flip-countdown">
        <div class="time-box"><span id="rb-days">00</span><p>Days</p></div>
        <div class="time-box"><span id="rb-hours">00</span><p>Hours</p></div>
        <div class="time-box"><span id="rb-minutes">00</span><p>Minutes</p></div>
        <div class="time-box"><span id="rb-seconds">00</span><p>Seconds</p></div>
      </div>

      <a href="https://wa.me/9779867221301?text=I want Rakshya Bandhan cake"
         target="_blank" class="order-btn">
         Order Now
      </a>
    </div>
    
    <!-- Father's Day -->
    <div class="event-box">
      <h3>🌸 Father's Day</h3>
      <p>Celebrate your dad with a special cake 💖</p>

      <div class="flip-countdown">
        <div class="time-box"><span id="fd-days">00</span><p>Days</p></div>
        <div class="time-box"><span id="fd-hours">00</span><p>Hours</p></div>
        <div class="time-box"><span id="fd-minutes">00</span><p>Minutes</p></div>
        <div class="time-box"><span id="fd-seconds">00</span><p>Seconds</p></div>
      </div>

      <a href="https://wa.me/9779867221301?text=I want Father's Day cake"
         target="_blank" class="order-btn">
         Order Now
      </a>
    </div>

  </div>
</section>

  

 
</section>

<!-- Contact / Map -->
<section id="contact">
  <h2>Find Us on Map</h2>
  <div class="map-container">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3533.5511559418815!2d85.33028537405147!3d27.669355327168677!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39eb198746b6aba3%3A0x275d892c608ba5ef!2sBajeko%20Cake!5e0!3m2!1sen!2snp!4v1773818571061!5m2!1sen!2snp" width="300" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    <p>Free delivery inside Kathmandu,Lalitpur,Bhaktapur.</p>
    <a href="https://www.google.com/maps/dir/?api=1&destination=27.66936597896528,85.33285541838701" target="_blank"><button class="book-btn">Get Directions</button></a>
  </div>
</section>


<!-- About Us--</--->

<section class="about-us" id="about-section" style="display:none;">

  <div class="about-overlay"></div>

  <div class="about-container">

    <!-- LEFT CONTENT -->
    <div class="about-left">

      <span class="about-tag">
        BAJEKO CAKE
      </span>

      <h2>
        We Create Cakes
        <br>
        That Make Moments
        <br>
        Unforgettable.
      </h2>

      <p class="about-description">
        Bajeko Cake is a premium artisan cake studio located in Gwarko,
        Lalitpur, Nepal. We specialize in luxury custom cakes designed
        for birthdays, weddings, engagements, anniversaries, baby showers,
        corporate events, and every meaningful celebration.
      </p>

      <p class="about-description">
        Every cake at Bajeko Cake is handcrafted with passion using
        premium ingredients, elegant finishing, modern artistry,
        and creative detailing. Our mission is simple —
        to turn your sweetest memories into edible art.
      </p>

      <p class="about-description">
        From minimalist luxury cakes to trending themed creations,
        floral wedding masterpieces, kids celebration cakes,
        bento cakes, and customized premium designs,
        we deliver experiences that taste as beautiful as they look.
      </p>

      <div class="about-features">

        <div class="feature-item">
          <i class="fas fa-cake-candles"></i>
          <span>Custom Luxury Cakes</span>
        </div>

        <div class="feature-item">
          <i class="fas fa-star"></i>
          <span>Premium Ingredients</span>
        </div>

        <div class="feature-item">
          <i class="fas fa-heart"></i>
          <span>Made With Passion</span>
        </div>

        <div class="feature-item">
          <i class="fas fa-truck"></i>
          <span>Fast Kathmandu Delivery</span>
        </div>

      </div>

      <div class="about-stats">

        <div class="stat-box">
          <h3>500+</h3>
          <p>Happy Customers</p>
        </div>

        <div class="stat-box">
          <h3>5★</h3>
          <p>Customer Ratings</p>
        </div>

        <div class="stat-box">
          <h3>2021</h3>
          <p>Founded</p>
        </div>
        <!-- CUSTOMER HIGHLIGHTS -->
<div class="customer-highlights">

  <div class="highlight-title">
    <span>💬 Customer Highlights</span>
    <h3>What Our Customers Say</h3>
  </div>

  <div class="review-grid">

    <div class="review-card">
      <div class="review-stars">★★★★★</div>

      <p class="review-text">
        “Absolutely loved the custom cake design and taste.
        The detailing was beautiful and delivery was perfectly on time.
        One of the best cake experiences in Kathmandu.”
      </p>

      <div class="review-user">
        <img src="https://lh3.googleusercontent.com/a-/ALV-UjW-nf0ScijqGvH4f1XsFErUkQhHmLDy2NLF0l2n0NM53WP51kg=s120-c-rp-mo-ba3-br100">
        <div>
          <h4>Parash Awale</h4>
          <span>Google Review</span>
        </div>
      </div>
    </div>

    <div class="review-card featured-review">
      <div class="review-stars">★★★★★</div>

      <p class="review-text">
        “The cake looked even better than the reference photo
        and tasted amazing. Premium quality, elegant finishing,
        and very friendly service. Highly recommended!”
      </p>

      <div class="review-user">
        <img src="https://lh3.googleusercontent.com/a/ACg8ocKYIwr9JpSNWhtmcYTJDSOjKJhxryKLfp2HRrZ6QxoEMeMcWA=s120-c-rp-mo-ba3-br100">
        <div>
          <h4>Kuldeep Pokhrel</h4>
          <span>Top Review</span>
        </div>
      </div>
    </div>

    <div class="review-card">
      <div class="review-stars">★★★★★</div>

      <p class="review-text">
        “Beautiful presentation, soft sponge, rich flavor,
        and amazing customization. Bajeko Cake made our
        celebration unforgettable.”
      </p>

      <div class="review-user">
        <img src="https://lh3.googleusercontent.com/a-/ALV-UjV2JKs4lSnbH02bFdxi1HoBMW51wpLQsLUZCG5ACbpdrcACcaYN=s120-c-rp-mo-ba3-br100">
        <div>
          <h4>Utsav Stha</h4>
          <span>Google Maps Review</span>
        </div>
      </div>
    </div>

  </div>

</div>
        
        
        
        
        
        

      </div>
      
      
      
      
      
      

      <a href="https://wa.me/9779867221301"
         target="_blank"
         class="about-btn">
         Order Your Dream Cake
      </a>

    </div>

    <!-- RIGHT IMAGES -->
    <div class="about-right">

      <div class="about-image image-1">
        <img src="https://i.postimg.cc/x8hYBHZd/1757957251368_3.jpg"
             alt="Luxury Cake">
      </div>

      <div class="about-image image-2">
        <img src="https://i.postimg.cc/J0vmSJFK/1773807815441_3.jpg"
             alt="Elegant Cake">
      </div>

      <div class="about-image image-3">
        <img src="https://i.postimg.cc/pdS5k7S6/1775455145183-2.jpg"
             alt="Premium Cake">
      </div>

    </div>

  </div>

</section>





<footer class="footer">
  <div class="footer-grid">

    <!-- LEFT : Logo + Slogan -->
    <div class="footer-box left">
      <img src="https://i.postimg.cc/FFcqKR6R/b04ca170-1-removebg-preview.png" class="footer-logo">
      <h3>Bajeko Cake</h3>
      <p class="slogan">Fresh is always best.</p>
    </div>

    <!-- MIDDLE : Contact -->
    <div class="footer-box">
      <h3>Contact Us</h3>
      <p>📧 bajekocake@gmail.com</p>
      <p>📞 +977-9867221301</p>
      <p>📍 Gwarko, Lalitpur</p>
    </div>

    <!-- RIGHT : Social -->
    <div class="footer-box">
      <h3>Follow Us</h3>

      <div class="footer-social">
        <a href="https://facebook.com/BAJEKOCAKE" target="_blank" class="facebook">
          <i class="fab fa-facebook-f"></i>
        </a>

        <a href="https://www.instagram.com/baje_ko_cake" target="_blank" class="instagram">
          <i class="fab fa-instagram"></i>
        </a>
      </div>

    </div>

  </div>

  <p class="copyright">© 2021 Bajeko Cake. Crafted with Love.</p>
</footer>

 <script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Bakery",
  "name": "Bajeko Cake",
  "image": "https://bajekocake.com.np/logo.png",
  "url": "https://bajekocake.com.np",
  "telephone": "+9779867221301",
  "priceRange": "$$",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Gwarko",
    "addressLocality": "Lalitpur",
    "addressRegion": "Bagmati",
    "postalCode": "44600",
    "addressCountry": "NP"
  },
  "areaServed": ["Kathmandu","Lalitpur","Bhaktapur"],
  "sameAs": [
    "https://facebook.com/BAJEKOCAKE",
    "https://instagram.com/baje_ko_cake"
  ]
}
</script>

<!-- WhatsApp Floating -->
<a href="https://wa.me/9779867221301" target="_blank" class="whatsapp-icon"><i class="fab fa-whatsapp"></i></a>

<!-- Messenger Floating -->
<a href="https://m.me/BAJEKOCAKE" 
   target="_blank" 
   class="messenger-icon">
   <i class="fab fa-facebook-messenger"></i>
</a>



<!-- Scripts -->
<script>
  // Navigation
 function hideAllSections(){
  document.getElementById('home-section').style.display='none';
  document.getElementById('products').style.display='none';
  document.getElementById('gallery-section').style.display='none';
  document.getElementById('about-section').style.display='none';
  document.getElementById('contact').style.display='none';
  document.getElementById('upcoming-event').style.display='none';
}

function showHome(){
  hideAllSections();
  document.getElementById('home-section').style.display='block';
  document.getElementById('upcoming-event').style.display='block';
  window.scrollTo({top:0,behavior:'smooth'});
}

function showProducts(){
hideAllSections();
document.getElementById('products').style.display='block';
document.getElementById('products').scrollIntoView({behavior:'smooth'});
}

function showGallery(){
hideAllSections();
document.getElementById('gallery-section').style.display='block';
filterGallery('all');
document.getElementById('gallery-section').scrollIntoView({behavior:'smooth'});
}

function showAbout(){
hideAllSections();
document.getElementById('about-section').style.display='block';
document.getElementById('about-section').scrollIntoView({behavior:'smooth'});
}

function showContact(){
  hideAllSections();
  document.getElementById('contact').style.display = 'block';
  document.getElementById('contact').scrollIntoView({behavior:'smooth'});
}



showHome();



  // WhatsApp Order
  function orderWhatsApp(product){
    const phone = "9779867221301";
    const url = `https://wa.me/${phone}?text=${encodeURIComponent(`Hello Bajeko Cake ,
I want to order: ${product}
Please share price and size.`)}`;
    window.open(url,'_blank');
  }

  // Product Filter
  function filterCategory(category){
const cards = document.querySelectorAll('.product-card');

cards.forEach(card=>{
if(category === "all"){
card.style.display = "block";
}
else if(card.getAttribute("data-category") === category){
card.style.display = "block";
}
else{
card.style.display = "none";
}
});
}

  // Gallery Filter
  const galleryImages = [
    /* Kid Cakes */
    {src:'https://i.postimg.cc/DyLW2Pmc/PXL_20251224_113332476_PORTRAIT.jpg', category:'kid'},
    {src:'https://i.postimg.cc/7PmQxsH3/1776662821347-3.jpg', category:'kid'},
    {src:'https://i.postimg.cc/W3gZ4zxM/1774960855220-2.jpg', category:'kid'},
    {src:'https://i.postimg.cc/4dYdjzDG/PXL_20250802_125718951.jpg', category:'kid'},
    {src:'https://i.postimg.cc/pdS5k7S6/1775455145183-2.jpg', category:'kid'},
    {src:'https://i.postimg.cc/zBKzhgz3/1774960044583-2.jpg', category:'kid'},
    {src:'https://i.postimg.cc/GhZ4mkdq/1775107167364-3.jpg', category:'kid'},
    {src:'https://i.postimg.cc/NMkT437N/PXL_20250722_112947331_PORTRAIT.jpg', category:'kid'},
    {src:'https://i.postimg.cc/JnLZjrJB/PXL_20250412_093744348_PORTRAIT_2.jpg', category:'kid'},
    {src:'https://i.postimg.cc/267vwsF4/PXL_20250429_141911346_PORTRAIT.jpg', category:'kid'},
    {src:'https://i.postimg.cc/bw4QNHwx/PXL_20241230_102811673_PORTRAIT_2.jpg', category:'kid'},
    {src:'https://i.postimg.cc/hjBTVDxD/PXL_20250223_112245511_PORTRAIT_2.jpg', category:'kid'},
    {src:'https://i.postimg.cc/zBrKTzWr/PXL_20240703_075616887_PORTRAIT_3.jpg', category:'kid'},
    {src:'https://i.postimg.cc/85SMLpv0/PXL_20250105_044821131_PORTRAIT_3.jpg', category:'kid'},
    {src:'https://i.postimg.cc/YCJGQLqb/1758286240421_2.jpg', category:'kid'},
    {src:'https://i.postimg.cc/sgtQ5GDm/1758372936233_2.jpg', category:'kid'},
    {src:'https://i.postimg.cc/GpGBK3HV/PXL_20251219_065311679_PORTRAIT_2_(1).jpg', category:'kid'},
     
    {src:'https://i.postimg.cc/pTvm6NFS/PXL_20250622_104617056.jpg', category:'kid'},
    
    

    /* Wedding Cakes */
    {src:'https://i.postimg.cc/8cRWtP1J/1776678198349-2.jpg', category:'wedding'},
    {src:'https://i.postimg.cc/PJWZ2rtv/1776678718048-2.jpg', category:'wedding'},
    {src:'https://i.postimg.cc/NFqm6rwk/1776678800067-2.jpg', category:'wedding'},
    {src:'https://i.postimg.cc/fynmc0hm/1776678982123-2.jpg', category:'wedding'},
    {src:'https://i.postimg.cc/8cQMRrV6/1776680251655-2.jpg', category:'wedding'},
    {src:'https://i.postimg.cc/sxYSwDVB/1776680444354-2.jpg', category:'wedding'},
    {src:'https://i.postimg.cc/gkmHCp1k/1777456041121-2.jpg', category:'wedding'},
    {src:'https://i.postimg.cc/d3Pr2TKT/1776681500120-2.jpg', category:'wedding'},
    {src:'https://i.postimg.cc/PJsYW8kv/1776681572439-2.jpg', category:'wedding'},
    /* Football Cakes */
    {src:'https://i.postimg.cc/zBLq70ds/1773993315025_2.jpg', category:'football'},
    {src:'https://i.postimg.cc/rmdqjQhH/1757956305870_2.jpg', category:'football'},
    {src:'https://i.postimg.cc/W3Ds8XWR/1773993502852_3.jpg', category:'football'},
    {src:'https://i.postimg.cc/Dyv1Cgbf/1777799020493-2.jpg', category:'football'},
    {src:'https://i.postimg.cc/ZR9JHVf1/1756982700362_2.jpg', category:'football'},
    {src:'https://i.postimg.cc/wvSgGLZj/PXL_20250409_095903230_PORTRAIT_2.jpg', category:'football'},
    {src:'https://i.postimg.cc/qMHpcc25/PXL_20250724_114313368_PORTRAIT.jpg', category:'football'},
    {src:'https://i.postimg.cc/htSg6Syy/PXL_20250622_063451460_PORTRAIT_2.jpg', category:'football'},
    /* Elegant Cakes */
    {src:'https://i.postimg.cc/J0vmSJFK/1773807815441_3.jpg', category:'elegant'},
    {src:'https://i.postimg.cc/BbksRDzg/1773747361217_3.jpg', category:'elegant'},
    {src:'https://i.postimg.cc/L53Xd0y4/1775287754015-2.jpg', category:'elegant'},
    {src:'https://i.postimg.cc/ZRkKWh2K/1775464904157-2.jpg', category:'elegant'},
    {src:'https://i.postimg.cc/C5XY9D2G/1758030051689.png', category:'elegant'},
    {src:'https://i.postimg.cc/rs3c7WHQ/1760514305142_2.jpg', category:'elegant'},
    {src:'https://i.postimg.cc/x8hYBHZd/1757957251368_3.jpg', category:'elegant'},
    {src:'https://i.postimg.cc/vTkMC9Kx/1758739521493_3.jpg', category:'elegant'},
    {src:'https://i.postimg.cc/ZY6nB1ny/1774961100650-2.jpg', category:'elegant'},
    {src:'https://i.postimg.cc/h4V8DZBc/1774960243175-2.jpg', category:'elegant'},
    {src:'https://i.postimg.cc/hv6gNxYt/1758221201169_2.jpg', category:'elegant'},
  ];

  function filterGallery(category){
  const galleryContainer = document.getElementById('gallery-container');
  galleryContainer.innerHTML='';

  galleryImages.forEach(item=>{
    if(category==='all' || item.category===category){
      const img = document.createElement('img');

      img.src = item.src;
      img.loading = "lazy"; // ✅ ADD THIS
      img.decoding = "async"; // ✅ smoother rendering
      img.onclick = () => openLightbox(img);

      galleryContainer.appendChild(img);
    }
  });
}



const cards = document.querySelectorAll('.product-card, .cake-card, .featured-card');

const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if(entry.isIntersecting){
      entry.target.style.opacity = 1;
      entry.target.style.transform = "translateY(0)";
    }
  });
});

cards.forEach(card => {
  card.style.opacity = 0;
  card.style.transform = "translateY(40px)";
  observer.observe(card);
});




  // Lightbox
  let currentIndex = 0;
let images = [];
let scale = 1;

// Open lightbox
function openLightbox(img, index = 0) {
  images = Array.from(document.querySelectorAll('.gallery img, .featured-card img, .cake-card img'));
  currentIndex = images.indexOf(img);

  document.getElementById("lightbox").style.display = "flex";
  document.getElementById("lightbox-img").src = img.src;
  scale = 1;
}

// Close
function closeLightbox() {
  document.getElementById("lightbox").style.display = "none";
}

// Slide navigation
function changeSlide(direction) {
  currentIndex += direction;

  if (currentIndex < 0) currentIndex = images.length - 1;
  if (currentIndex >= images.length) currentIndex = 0;

  document.getElementById("lightbox-img").src = images[currentIndex].src;
  scale = 1;
  updateZoom();
}

// Zoom (scroll)
const lightboxImg = document.getElementById("lightbox-img");

lightboxImg.addEventListener("wheel", (e) => {
  e.preventDefault();
  scale += e.deltaY * -0.001;
  scale = Math.min(Math.max(1, scale), 3);
  updateZoom();
});

function updateZoom() {
  lightboxImg.style.transform = `scale(${scale})`;
}

// Swipe (mobile)
let startX = 0;

lightboxImg.addEventListener("touchstart", (e) => {
  startX = e.touches[0].clientX;
});

lightboxImg.addEventListener("touchend", (e) => {
  let endX = e.changedTouches[0].clientX;

  if (startX - endX > 50) changeSlide(1);
  if (endX - startX > 50) changeSlide(-1);
});

// ✨ Sparkle Generator
function createSparkles() {
  const section = document.querySelector('.upcoming-event');

  setInterval(() => {
    const sparkle = document.createElement('div');
    sparkle.classList.add('sparkle');

    sparkle.style.left = Math.random() * 100 + '%';
    sparkle.style.top = Math.random() * 100 + '%';

    section.appendChild(sparkle);

    setTimeout(() => {
      sparkle.remove();
    }, 3000);
  }, 200);
}

createSparkles();

  // Upcoming Event Countdown
// Event Dates
const fathersDay = new Date("September 11, 2026 00:00:00").getTime();
const rakshyaBandhan = new Date("August 28, 2026 00:00:00").getTime();

function updateCountdown(targetDate, ids) {
  const now = new Date().getTime();
  const distance = targetDate - now;

  if (distance < 0) return;

  const days = String(Math.floor(distance / (1000*60*60*24))).padStart(2,'0');
  const hours = String(Math.floor((distance % (1000*60*60*24))/(1000*60*60))).padStart(2,'0');
  const minutes = String(Math.floor((distance % (1000*60*60))/(1000*60))).padStart(2,'0');
  const seconds = String(Math.floor((distance % (1000*60))/1000)).padStart(2,'0');

  document.getElementById(ids.days).innerText = days;
  document.getElementById(ids.hours).innerText = hours;
  document.getElementById(ids.minutes).innerText = minutes;
  document.getElementById(ids.seconds).innerText = seconds;
}

// Run both timers
setInterval(() => {
  updateCountdown(fathersDay, {
    days: "fd-days",
    hours: "fd-hours",
    minutes: "fd-minutes",
    seconds: "fd-seconds"
  });

  updateCountdown(rakshyaBandhan, {
    days: "rb-days",
    hours: "rb-hours",
    minutes: "rb-minutes",
    seconds: "rb-seconds"
  });
}, 1000);
</script>
</body>
</html>
