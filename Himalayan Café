<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Himalayan Café | Fresh Food & Great Coffee</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  scroll-behavior:smooth;
}

body{
  font-family:Arial, sans-serif;
  background:#faf7f2;
  color:#29211d;
  line-height:1.6;
}

/* NAVBAR */
nav{
  position:fixed;
  top:0;
  left:0;
  width:100%;
  z-index:1000;
  padding:18px 25px;
  background:rgba(35,22,17,0.94);
  backdrop-filter:blur(10px);
  display:flex;
  justify-content:center;
  gap:35px;
}

nav a{
  color:white;
  text-decoration:none;
  font-weight:bold;
  font-size:16px;
  transition:0.3s;
}

nav a:hover{
  color:#e7a45b;
}

/* HERO */
.hero{
  min-height:100vh;
  padding:120px 25px 80px;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  color:white;

  background:
    linear-gradient(rgba(30,18,13,0.60),rgba(30,18,13,0.70)),
    url("https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?auto=format&fit=crop&w=1600&q=85");

  background-size:cover;
  background-position:center;
}

.hero-content{
  max-width:850px;
  animation:fadeUp 1.2s ease;
}

.small-title{
  letter-spacing:5px;
  font-size:15px;
  color:#f0bd7b;
  font-weight:bold;
}

.hero h1{
  font-size:clamp(48px,10vw,92px);
  line-height:1.05;
  margin:20px 0;
  font-weight:800;
}

.hero p{
  font-size:20px;
  max-width:650px;
  margin:0 auto 35px;
  color:#f3eee9;
}

.btn{
  display:inline-block;
  padding:15px 30px;
  border-radius:50px;
  background:#d98a45;
  color:white;
  text-decoration:none;
  font-weight:bold;
  transition:0.3s;
  box-shadow:0 10px 30px rgba(0,0,0,0.25);
}

.btn:hover{
  transform:translateY(-4px);
  background:#ed9f57;
}

/* GENERAL */
section{
  padding:90px 20px;
  max-width:1150px;
  margin:auto;
}

.section-title{
  text-align:center;
  margin-bottom:50px;
}

.section-title span{
  color:#c87532;
  font-size:14px;
  letter-spacing:3px;
  font-weight:bold;
}

.section-title h2{
  font-size:42px;
  margin-top:8px;
  color:#38251c;
}

/* ABOUT */
.about{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:45px;
  align-items:center;
}

.about-image{
  min-height:400px;
  border-radius:25px;
  background:
    url("https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=1000&q=85")
    center/cover;
  box-shadow:0 20px 45px rgba(60,35,20,0.18);
}

.about-text h3{
  font-size:30px;
  color:#38251c;
  margin-bottom:18px;
}

.about-text p{
  color:#665c56;
  font-size:17px;
  margin-bottom:20px;
}

.features{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:15px;
}

.feature{
  background:white;
  padding:18px;
  border-radius:15px;
  box-shadow:0 8px 25px rgba(0,0,0,0.06);
}

.feature strong{
  display:block;
  color:#38251c;
}

/* MENU */
.menu{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:22px;
}

.card{
  background:white;
  border-radius:22px;
  overflow:hidden;
  box-shadow:0 10px 30px rgba(0,0,0,0.08);
  transition:0.35s;
}

.card:hover{
  transform:translateY(-8px);
  box-shadow:0 18px 40px rgba(0,0,0,0.13);
}

.card-image{
  height:190px;
  background-size:cover;
  background-position:center;
}

.img1{
  background-image:url("https://images.unsplash.com/photo-1498837167922-ddd27525d352?auto=format&fit=crop&w=800&q=80");
}

.img2{
  background-image:url("https://images.unsplash.com/photo-1599487488170-d11ec9c172f0?auto=format&fit=crop&w=800&q=80");
}

.img3{
  background-image:url("https://images.unsplash.com/photo-1461023058943-07fcbe16d735?auto=format&fit=crop&w=800&q=80");
}

.img4{
  background-image:url("https://images.unsplash.com/photo-1544787219-7f47ccb76574?auto=format&fit=crop&w=800&q=80");
}

.img5{
  background-image:url("https://images.unsplash.com/photo-1528735602780-2552fd46c7af?auto=format&fit=crop&w=800&q=80");
}

.img6{
  background-image:url("https://images.unsplash.com/photo-1519915028121-7d3463d20b13?auto=format&fit=crop&w=800&q=80");
}

.card-content{
  padding:22px;
}

.card-content h3{
  font-size:22px;
  color:#38251c;
}

.card-content p{
  color:#777;
  margin:8px 0;
}

.price{
  color:#c87532 !important;
  font-size:20px;
  font-weight:bold;
}

/* SPECIAL SECTION */
.special{
  max-width:1100px;
  margin:20px auto 90px;
  border-radius:30px;
  padding:60px 30px;
  text-align:center;
  color:white;

  background:
    linear-gradient(rgba(50,29,19,0.82),rgba(50,29,19,0.82)),
    url("https://images.unsplash.com/photo-1445116572660-236099ec97a0?auto=format&fit=crop&w=1400&q=85")
    center/cover;
}

.special h2{
  font-size:40px;
  margin:12px 0;
}

.special p{
  max-width:650px;
  margin:0 auto 25px;
  color:#eee;
}

/* GALLERY */
.gallery{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:15px;
}

.gallery div{
  height:240px;
  border-radius:20px;
  background-size:cover;
  background-position:center;
  transition:0.3s;
}

.gallery div:hover{
  transform:scale(1.03);
}

.g1{
  background-image:url("https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=900&q=80");
}

.g2{
  background-image:url("https://images.unsplash.com/photo-1552566626-52f8b828add9?auto=format&fit=crop&w=900&q=80");
}

.g3{
  background-image:url("https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=900&q=80");
}

.g4{
  background-image:url("https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=900&q=80");
}

.g5{
  background-image:url("https://images.unsplash.com/photo-1515003197210-e0cd71810b5f?auto=format&fit=crop&w=900&q=80");
}

.g6{
  background-image:url("https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=900&q=80");
}

/* HOURS */
.hours-box{
  max-width:700px;
  margin:auto;
  background:white;
  padding:30px;
  border-radius:22px;
  box-shadow:0 10px 30px rgba(0,0,0,0.07);
}

.hour{
  display:flex;
  justify-content:space-between;
  padding:14px 0;
  border-bottom:1px solid #eee;
}

.hour:last-child{
  border-bottom:none;
}

/* VISIT */
.visit{
  background:#f0e4d8;
  max-width:100%;
  padding:80px 20px;
}

.visit-inner{
  max-width:900px;
  margin:auto;
  text-align:center;
}

.visit-inner h2{
  font-size:42px;
  color:#38251c;
  margin-bottom:20px;
}

.contact-info{
  margin:25px 0;
  font-size:18px;
}

.contact-info p{
  margin:8px;
}

/* FOOTER */
footer{
  background:#241611;
  color:#ddd;
  text-align:center;
  padding:35px 20px;
}

footer h3{
  color:white;
  font-size:25px;
  margin-bottom:8px;
}

footer p{
  color:#aaa;
}

/* ANIMATION */
@keyframes fadeUp{
  from{
    opacity:0;
    transform:translateY(30px);
  }
  to{
    opacity:1;
    transform:translateY(0);
  }
}

/* MOBILE */
@media(max-width:800px){

  nav{
    gap:20px;
    padding:16px 10px;
  }

  nav a{
    font-size:14px;
  }

  .hero{
    min-height:90vh;
  }

  .hero h1{
    font-size:50px;
  }

  .hero p{
    font-size:17px;
  }

  section{
    padding:65px 18px;
  }

  .section-title h2{
    font-size:34px;
  }

  .about{
    grid-template-columns:1fr;
  }

  .about-image{
    min-height:300px;
  }

  .menu{
    grid-template-columns:1fr;
  }

  .gallery{
    grid-template-columns:1fr 1fr;
  }

  .gallery div{
    height:180px;
  }

  .special h2{
    font-size:32px;
  }

  .visit-inner h2{
    font-size:34px;
  }
}

@media(max-width:450px){

  .hero h1{
    font-size:43px;
  }

  .features{
    grid-template-columns:1fr;
  }

  .gallery{
    grid-template-columns:1fr;
  }

  .gallery div{
    height:220px;
  }
}
</style>
</head>

<body>

<!-- NAVIGATION -->
<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#menu">Menu</a>
  <a href="#gallery">Gallery</a>
  <a href="#visit">Contact</a>
</nav>

<!-- HERO -->
<header class="hero" id="home">
  <div class="hero-content">
    <div class="small-title">WELCOME TO</div>

    <h1>Himalayan Café</h1>

    <p>
      Fresh food, handcrafted drinks and warm moments
      inspired by the spirit of the Himalayas.
    </p>

    <a href="#menu" class="btn">Explore Our Menu →</a>
  </div>
</header>

<!-- ABOUT -->
<section id="about">

  <div class="section-title">
    <span>OUR STORY</span>
    <h2>A Place To Slow Down</h2>
  </div>

  <div class="about">

    <div class="about-image"></div>

    <div class="about-text">

      <h3>Good food. Good coffee. Good moments.</h3>

      <p>
        Himalayan Café is a cozy place to meet friends,
        enjoy delicious food and take a relaxing break
        from a busy day.
      </p>

      <p>
        From comforting momos to refreshing coffee,
        every item is prepared to make your visit special.
      </p>

      <div class="features">

        <div class="feature">
          ☕
          <strong>Fresh Drinks</strong>
          Carefully prepared beverages.
        </div>

        <div class="feature">
          🥟
          <strong>Fresh Food</strong>
          Delicious food made for you.
        </div>

        <div class="feature">
          ❤️
          <strong>Cozy Atmosphere</strong>
          Relax and enjoy your time.
        </div>

        <div class="feature">
          ✨
          <strong>Good Moments</strong>
          A place worth coming back to.
        </div>

      </div>

    </div>

  </div>

</section>

<!-- MENU -->
<section id="menu">

  <div class="section-title">
    <span>WHAT WE SERVE</span>
    <h2>Our Popular Menu</h2>
  </div>

  <div class="menu">

    <div class="card">
      <div class="card-image img1"></div>
      <div class="card-content">
        <h3>🥟 Veg Momos</h3>
        <p>Soft vegetable-filled momos served fresh.</p>
        <p class="price">₹80</p>
      </div>
    </div>

    <div class="card">
      <div class="card-image img2"></div>
      <div class="card-content">
        <h3>🥟 Chicken Momos</h3>
        <p>Juicy chicken-filled momos with great flavor.</p>
        <p class="price">₹120</p>
      </div>
    </div>

    <div class="card">
      <div class="card-image img3"></div>
      <div class="card-content">
        <h3>🧋 Cold Coffee</h3>
        <p>Chilled creamy coffee for a refreshing break.</p>
        <p class="price">₹90</p>
      </div>
    </div>

    <div class="card">
      <div class="card-image img4"></div>
      <div class="card-content">
        <h3>🍵 Masala Tea</h3>
        <p>Warm aromatic tea with a delicious spice blend.</p>
        <p class="price">₹40</p>
      </div>
    </div>

    <div class="card">
      <div class="card-image img5"></div>
      <div class="card-content">
        <h3>🥪 Veg Sandwich</h3>
        <p>Fresh vegetables packed into a tasty sandwich.</p>
        <p class="price">₹100</p>
      </div>
    </div>

    <div class="card">
      <div class="card-image img6"></div>
      <div class="card-content">
        <h3>🍰 Sweet Treat</h3>
        <p>A delicious little treat to finish your visit.</p>
        <p class="price">₹70</p>
      </div>
    </div>

  </div>

</section>

<!-- SPECIAL -->
<div class="special">

  <span class="small-title">YOUR NEXT COFFEE BREAK</span>

  <h2>Come. Relax. Enjoy.</h2>

  <p>
    Whether you're meeting friends or simply taking
    some time for yourself, Himalayan Café is ready
    to welcome you.
  </p>

  <a href="#visit" class="btn">Plan Your Visit →</a>

</div>

<!-- GALLERY -->
<section id="gallery">

  <div class="section-title">
    <span>EXPLORE</span>
    <h2>Inside Himalayan Café</h2>
  </div>

  <div class="gallery">
    <div class="g1"></div>
    <div class="g2"></div>
    <div class="g3"></div>
    <div class="g4"></div>
    <div class="g5"></div>
    <div class="g6"></div>
  </div>

</section>

<!-- HOURS -->
<section>

  <div class="section-title">
    <span>WHEN TO VISIT</span>
    <h2>Opening Hours</h2>
  </div>

  <div class="hours-box">

    <div class="hour">
      <strong>Monday – Friday</strong>
      <span>9:00 AM – 9:00 PM</span>
    </div>

    <div class="hour">
      <strong>Saturday</strong>
      <span>9:00 AM – 10:00 PM</span>
    </div>

    <div class="hour">
      <strong>Sunday</strong>
      <span>10:00 AM – 9:00 PM</span>
    </div>

  </div>

</section>

<!-- VISIT -->
<div class="visit" id="visit">

  <div class="visit-inner">

    <div class="section-title">
      <span>COME SAY HELLO</span>
      <h2>Visit Himalayan Café</h2>
    </div>

    <div class="contact-info">
      <p>📍 <strong>Siliguri, West Bengal</strong></p>
      <p>☕ Fresh food • Great coffee • Good moments</p>
    </div>

    <a
      href="https://wa.me/919999999999"
      class="btn"
      target="_blank"
    >
      💬 WhatsApp Us
    </a>

  </div>

</div>

<!-- FOOTER -->
<footer>

  <h3>Himalayan Café</h3>

  <p>
    Fresh food. Great coffee. Good moments.
  </p>

  <p style="margin-top:15px;">
    © 2026 Himalayan Café
  </p>

</footer>

</body>
</html>
