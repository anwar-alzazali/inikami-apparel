<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>inikami-konveksi</title>
    <!-- Include your CSS and JavaScript files -->
    <link rel="stylesheet" href="css/style.css" />

    <!-- Add any additional meta tags, favicon, etc. -->
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css"
    />
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar">
      <a href="#home" class="navbar-logo">INI<span>KAMI</span>.</a>

      <div class="navbar-nav">
        <a href="#home">Home</a>
        <a href="#about">Profile</a>
        <a href="#produk">Produk</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Kontak</a>
      </div>
      <div class="navbar-extra">
        <a href="#search-box" id="search-button"
          ><i class="bi bi-search"></i>
        ></a>
        <a href="#" id="shopping-cart"><i class="bi bi-cart3"></i></a>
        <a href="#hamburger-menu" id="hamburger-menu"
          ><i class="bi bi-list"></i></a>
      </div>
      <div class="search-form">
        <input type="search" id="search-box" placeholder="search..." />
        <label for="search-box"><i class="bi bi-check-lg"></i></label>
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
      <main class="content">
        <h1>We Provide Your<span> Solutions</span></h1>
        <p>Your success is our priority.</p>
        <a href="#contact" class="cta">Get in Touch</a>
      </main>
    </section>
    <!-- About Us Section -->
    <section class="about" id="about">
      <h2>Siapa Kami ?</h2>
      <div class="row">
        <div class="about-img">
         <img src="img/header-bg.jpg" alt="">
        </div>

        <div class="about-content">
          <h3>
            Kenapa harus percayakan produk kepada
            <a href="#home"><span> INIKAMI</span></a> ?
          </h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi
            repellat expedita accusamus impedit soluta vero dolores dolor maxime
            a nostrum sunt nobis, iure iusto libero, dolorum, ab officiis
            praesentium est animi? Deserunt omnis aliquid ipsa autem!
          </p>
        </div>
      </div>
      <div class="row">
        <div class="about-img">
        <img src="img/annie.jpg" alt="" />
        </div>

        <div class="about-content">
          <h3>
            Kenapa harus percayakan produk kepada
            <a href="#home"><span> INIKAMI</span></a> ?
          </h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi
            repellat expedita accusamus impedit soluta vero dolores dolor maxime
            a nostrum sunt nobis, iure iusto libero, dolorum, ab officiis
            praesentium est animi? Deserunt omnis aliquid ipsa autem!
          </p>
        </div>
      </div>
    </section>

    <!-- Your Menu Sections Here -->
    <section id="produk" class="produk">
      <h2>Produk</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt
        inventore explicabo nisi amet labore cupiditate commodi facere beatae in
        fugiat?
      </p>
      <div class="row">
        <div class="menu-card">
          <img src="img/rockstar.jpg" alt="" class="menu-card-img" />
          <h3 class="menu-card-title">-- T-SHIRT --</h3>
          <p class="menu-card-price">IDR 150K</p>
        </div>
        <div class="menu-card">
          <img src="img/rockstar.jpg" alt="" class="menu-card-img" />
          <h3 class="menu-card-title">-- T-SHIRT --</h3>
          <p class="menu-card-price">IDR 150K</p>
        </div>
        <div class="menu-card">
          <img src="img/rockstar.jpg" alt="" class="menu-card-img" />
          <h3 class="menu-card-title">-- T-SHIRT --</h3>
          <p class="menu-card-price">IDR 150K</p>
        </div>
        <div class="menu-card">
          <img src="img/rockstar.jpg" alt="" class="menu-card-img" />
          <h3 class="menu-card-title">-- T-SHIRT --</h3>
          <p class="menu-card-price">IDR 150K</p>
        </div>
        <div class="menu-card">
          <img src="img/rockstar.jpg" alt="" class="menu-card-img" />
          <h3 class="menu-card-title">-- T-SHIRT --</h3>
          <p class="menu-card-price">IDR 150K</p>
        </div>
        <div class="menu-card">
          <img src="img/rockstar.jpg" alt="" class="menu-card-img" />
          <h3 class="menu-card-title">-- T-SHIRT --</h3>
          <p class="menu-card-price">IDR 150K</p>
        </div>
      </div>
    </section>

    <!-- section contact -->

    <section id="contact" class="contact">
      <h2>Kontak</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis,
        tenetur.
      </p>
      <div class="row">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m17!1m12!1m3!1d1177.661703267421!2d107.55555929067039!3d-6.870701370865783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m2!1m1!2zNsKwNTInMTEuMiJTIDEwN8KwMzMnMTkuNCJF!5e0!3m2!1sen!2sid!4v1706704696069!5m2!1sen!2sid"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
          class="maps"
        ></iframe>
        <form action="">
          <div class="input-group">
            <i class="bi bi-person"></i>
            <input type="text" placeholder="nama" />
          </div>
          <div class="input-group">
            <i class="bi bi-envelope-at"></i>
            <input type="text" placeholder="email" />
          </div>
          <div class="input-group">
            <i class="bi bi-whatsapp" id="bi-whatsapp"></i>
            <input type="text" placeholder="whatsapp" />
          </div>
        </form>
      </div>
    </section>

    <!-- section footer -->
    <section>
      <footer class="footer">
        <p>&copy; 2024 <span> INIKAMI.</span> All rights reserved.</p>

        <!-- Social Media Icons -->
        <div class="social-icons">
          <a href="https://www.facebook.com/?_rdc=1&_rdr" target="_blank"
            ><i class="bi bi-facebook"></i
          ></a>
          <a href="https://twitter.com/" target="_blank"
            ><i class="bi bi-twitter"></i
          ></a>
          <a href="https://www.instagram.com/" target="_blank"
            ><i class="bi bi-instagram"></i
          ></a>
          <a href="https://www.instagram.com/" target="_blank"
            ><i class="bi bi-tiktok"></i
          ></a>
          <!-- Tambahkan ikon media sosial lainnya sesuai kebutuhan -->
        </div>
      </footer>
    </section>

    <!-- Feather Icons -->
  
    <!-- Call the Feather Icons replacement script -->
    
    <script src="js/script.js"></script>
  </body>
</html>
