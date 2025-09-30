<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meet The Girls NGO</title>
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box;}
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
      background: url('meet2.jpg') center/cover no-repeat fixed; /* 👈 NGO BACKGROUND IMAGE */
    }
    a {text-decoration: none; color: inherit;}
    img {max-width: 100%; display: block;}

    header {
      background: rgba(0,0,0,0.8);
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px;
    }
    nav .logo img {height: 50px;}
    nav ul {list-style: none; display: flex; gap: 20px;}
    nav ul li a:hover {color: red;}

    .hero {
      background: rgba(0,0,0,0.6);
      color: white;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }
    .hero h1 {
      font-size: 3em;
      background: rgba(255,255,255,0.1);
      padding: 20px;
      border-radius: 10px;
    }

    section {
      padding: 60px 20px;
      background: rgba(255,255,255,0.9);
      margin: 20px;
      border-radius: 10px;
    }

    .about h2 {color: red; margin-bottom: 20px;}

    .programs {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .program {
      padding: 20px;
      background: white;
      border: 1px solid #ddd;
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .program:hover {transform: scale(1.05);}

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 10px;
    }
    .gallery img {border-radius: 10px;}

    .aka-food {
      background: linear-gradient(to right, green, yellow);
      color: white;
      text-align: center;
      padding: 60px 20px;
      border-radius: 10px;
    }
    .aka-food h2 {color: blue; margin-bottom: 20px;}
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      color: #333;
      padding: 15px;
      border-radius: 10px;
      transition: 0.3s;
    }
    .product:hover {transform: scale(1.05);}

    .contact {
      background: #222;
      color: white;
      text-align: center;
      padding: 40px 20px;
      border-radius: 10px;
    }
    .contact a {color: red; font-weight: bold;}

    footer {
      background: black;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <nav>
      <div class="logo">
        <img src="meet-logo.png" alt="Meet The Girls Logo">
      </div>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#programs">Programs</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#aka-food">AKA FOOD</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero" id="home">
    <h1>Empowering Women in Science & Education</h1>
  </section>

  <section class="about" id="about">
    <h2>About Meet The Girls</h2>
    <p>
      Meet The Girls is a non-governmental organization committed to promoting women in science,
      supporting education, and empowering women to become leaders in their communities.
    </p>
  </section>
  <section class="about" id="about">
  <h2>About the Founder</h2>
  <p>
    <div>  
      <img src="autor1.jpg" alt="founder">
      </div>
      <h3>Dr. Agbor Evelyn Agbor (PHD)</h3><br>
      Food Processing Technologist<br>
      DIPES II BIOLOGY<br>
      SDM at G.B.H.S. Bafoussam<br>
      Founder and coordinator of Meet the Girls Cameroon and S.T.E.M. Club G.B.H.S. BAFOUSSAM<br>
  </p>
  </section>

  <section id="programs">
    <h2 style="text-align:center; color:red;">Our Programs</h2>
    <div class="programs">
      <div class="program">
        <h3>STEM Education</h3>
        <p>Workshops and mentorship to inspire young girls in science and technology.</p>
      </div>
      <div class="program">
        <h3>Community Empowerment</h3>
        <p>Empowering women with skills for leadership and entrepreneurship.</p>
      </div>
      <div class="program">
        <h3>Scholarships</h3>
        <p>Supporting education for girls from underserved backgrounds.</p>
      </div>
    </div>
  </section>

  <section id="gallery">
    <h2 style="text-align:center; color:red;">Gallery</h2>
    <div class="gallery">
      <img src="meet1.jpg" alt="Meet The Girls Event 1">
      <img src="meet2.jpg" alt="Meet The Girls Event 2">
      <img src="meet3.jpg" alt="Meet The Girls Event 3">
      <img src="meet4.jpg" alt="Meet The Girls Event 4">
      <img src="meet5.jpg" alt="Meet The Girls Event 5">
    </div>
  </section>

  <section class="aka-food" id="aka-food">
    <img src="aka-logo.png" alt="AKA FOOD Logo" style="height:80px; margin-bottom:20px;">
    <h2>AKA FOOD Products</h2>
    <p>We produce healthy and natural food products including powder onion, plantain flour, potato flour, and more.</p>
    <div class="products">
      <div class="product">
        <img src="aka1.jpg" alt="Production of flour">
        <h3>Soya Bean Processing</h3>
      </div>
      <div class="product">
        <img src="aka2.jpg" alt="Product 2">
        <h3>Plantain Flour</h3>
      </div>
      <div class="product">
        <img src="aka3.jpg" alt="Product 3">
        <h3>Pap Powder</h3>
      </div>
      <div class="product">
        <img src="aka4.jpg" alt="Product 4">
        <h3>Biscuit Produced from Sweet Potato Flour</h3>
      </div>
      <div class="product">
        <img src="aka5.jpg" alt="Product 5">
        <h3>Other Products</h3>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Phone: <a href="tel:+237675033663">+237 675 033 663</a></p>
    <p>Email: eyungong81@gmail.com</p>
    <p>Location: Ngouache-Bafoussam</p>
  </section>

  <footer>
    <p>&copy; 2025 Meet The Girls NGO | All Rights Reserved</p>
  </footer>

</body>
</html>
