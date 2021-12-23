<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
   <header>
    <div class="container">
      <div class="nav">
        <div class="menu-toggle">
          <i class="fas fa-bars"></i> <i class="fas fa-times"></i>
        </div>
        <a href="index.html" class="logo"><img src="./assets/logo-rosa.png" art="logo" /></a>
        <ul class="nav-list">
          <li class="nav-item">
            <a href="index.html" class="navi-link active">Home</a>
          </li>
          <li class="nav-item"><a href="#" class="navi-link">Menu</a></li>
          <li class="nav-item">
            <a href="#" class="navi-link">Reservations</a>
          </li>
          <li class="nav-item"><a href="#" class="navi-link">News</a></li>
          <li class="nav-item"><a href="#" class="navi-link">Shop</a></li>
          <li class="nav-item"><a href="#" class="navi-link">Contact</a></li>
        </ul>
      </div>
    </div>
  </header>
 
  <section class="hero" id="hero">
    <div class="container">
      <h2 class="sub-headline"><span class="first-letter">W</span>elcome</h2>
      <h1 class="headline">THE ROSA</h1>
      <div class="headline-description">
        <div class="separator">
          <div class="line line-left"></div>
          <div class="asterisk"><i class="fas fa-asterisk"></i></div>
          <div class="line line-right"></div>
        </div>
        <div class="single-animation">
          <h5>READY TO BE OPENED</h5>
          <a href="#" class="btn cta-btn">Explorer</a>
        </div>
      </div>
    </div>
  </section>
 
  <section class="story">
    <div class="container">
      <div class="restaurant-info">
        <div class="restaurant-description padding-right animate-left">
          <div class="global-headline">
            <h2 class="sub-headline">
              <span class="first-letter">D</span>iscover
            </h2>
            <h1 class="headline headline-dark">Our Story</h1>
            <div class="asterisk"><i class="fas fa-asterisk"></i></div>
          </div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam,
            laborum. Incidunt voluptatibus laboriosam, ipsum dolore, est
            commodi. Harum ipsum, accusantium eveniet quibusdam laborum
            dolores nobis, repellat ipsa sed magnam quas.
          </p>
          <a href="#" class="btn body-btn">About us</a>
        </div>
        <div class="restaurant-img animate-right">
          <img
            src="https://images.unsplash.com/photo-1550966871-3ed3cdb5ed0c?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            alt="" />
        </div>
      </div>
    </div>
  </section>
 
  <section class="taateful-recipes between">
    <div class="container">
      <div class="global-headline">
        <div class="animate-top">
          <h2 class="sub-headline">
            <span class="first-letter">T</span>asteful
          </h2>
        </div>
        <div class="annimate-bottom">
          <h1 class="headline">Recipes</h1>
        </div>
      </div>
    </div>
  </section>
 
  <section class="discover-our-menu">
    <div class="container">
      <div class="restaurant-info">
        <div class="image-group padding-right animate-left">
            <img src="https://images.unsplash.com/photo-1542528180-a1208c5169a5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1177&q=80" alt="" />
          <img
            src="https://images.unsplash.com/photo-1514361892635-6b07e31e75f9?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            alt="" />
          <img
            src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            alt="" />
          <img src="https://images.unsplash.com/photo-1529928520614-7c76e2d99740?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80" alt="" />
        </div>
        <div class="restaurant-description animate-right">
          <div class="global-headline">
            <h2 class="sub-headline">
              <span class="first-letter">D</span>iscover
            </h2>
            <h1 class="headline headline-dark">Menu</h1>
            <div class="asterisk"><i class="fas fa-asterisk"></i></div>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum
              numquam explicabo iusto mollitia. Voluptatem tempora eius quidem
              debitis repellat ipsum deleniti assumenda voluptas. Quam
              doloremque quia veniam voluptates illo, deleniti.
            </p>
            <a href="#" class="btm body-btn">View the full menu</a>
          </div>
        </div>
      </div>
    </div>
  </section>
 
  <section class="perfect-blend between">
    <div class="container">
      <div class="global-headline">
        <div class="animate-top">
          <h2 class="sub-headline">
            <span class="first-letter">T</span>he perfect
          </h2>
        </div>
        <div class="annimate-bottom">
          <h1 class="headline">Blend</h1>
        </div>
      </div>
    </div>
  </section>
 
  <section class="culinary-delight">
    <div class="container">
      <div class="restaurant-info">
        <div class="restaurant-description padding-right animate-left">
          <div class="global-headline">
            <h2 class="sub-headline">
              <span class="first-letter">C</span>ulinary
            </h2>
            <h1 class="headline headline-dark">Delight</h1>
            <div class="asterisk"><i class="fas fa-asterisk"></i></div>
          </div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam,
            laborum. Incidunt voluptatibus laboriosam, ipsum dolore, est
            commodi. Harum ipsum, accusantium eveniet quibusdam laborum
            dolores nobis, repellat ipsa sed magnam quas.
          </p>
          <a href="#" class="btn body-btn">Make a reservation</a>
        </div>
        <div class="image-group">
          <img class="animate-top"
            src="https://images.unsplash.com/photo-1429554513019-6c61c19ffb7e?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=634&q=80"
            alt="" />
          <img class="animate-bottom" src="https://images.unsplash.com/photo-1600663791817-d74f5196ba29?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1974&q=80" alt="" />
        </div>
      </div>
    </div>
  </section>
 
  <footer>
    <div class="container">
      <div class="back-to-top">
        <a href="#hero"><i class="fas fa-chevron-up"></i></a>
      </div>
      <div class="footer-content">
        <div class="footer-content-about animate-top">
          <h4>About Rosa</h4>
          <div class="asterisk"><i class="fas fa-asterisk"></i></div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quis
            ipsam nisi maiores voluptates voluptatibus dolorem ab, aliquid
            fugiat consequuntur molestias est. Quidem laborum aperiam tempora,
            consectetur dolores et quia repellendus.
          </p>
        </div>
        <div class="footer-content-divider animate-bottom">
          <div class="social-media">
            <h4>Follow along</h4>
            <ul class="social-icons">
              <li>
                <a href="#"><i class="fab fa-twitter"></i></a>
              </li>
              <li>
                <a href="#"><i class="fab fa-facebook-square"></i></a>
              </li>
              <li>
                <a href="#"><i class="fab fa-pinterest"></i></a>
              </li>
              <li>
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
              </li>
              <li>
                <a href="#"><i class="fab fa-tripadvisor"></i></a>
              </li>
            </ul>
          </div>
          <div class="newsletter-container">
            <h4>Newsletter</h4>
            <form action="" class="newsletter-from">
              <input type="text" class="newsletter-input" placeholder="Your email address...." />
              <button class="newsletter-btn" type="submit">
                <i class="fas fa-envelope"></i>
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
    <small class="copy-light">&copy;2021 ROSA</small>
  </footer>
</template>

