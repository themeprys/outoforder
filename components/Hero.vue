<template>
<section class="hero is-large">
  <div class="hero-head">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <nuxt-link to="/" class="navbar-item">
            <img src="~/static/img/iman_logo.svg" alt="Iman Fattah" height="100px">
          </nuxt-link>
          <!-- <div class="mt-5 navbar-burger">
          <a href="/files/Resume_Iman_Fattah.pdf" download>
                Resume <i class="fas fa-download"></i>
          </a>
          </div> -->
          <!-- <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarImn">
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a> -->
        </div>
        <div id="navbarImn" class="navbar-menu">
          <div class="navbar-end">
            <nuxt-link class="navbar-item" to="/">
              Rupa Suara
            </nuxt-link>
            <nuxt-link class="navbar-item" to="/credits">
              Tentang Buku
            </nuxt-link>
            <nuxt-link class="navbar-item" to="/tour">
              Bedah Buku
            </nuxt-link>
            <nuxt-link class="navbar-item is-active" to="/about">
              Tentang Saya
            </nuxt-link>
            <nuxt-link class="navbar-item"  to="/contact">
              Kontak
            </nuxt-link>
            <!-- <a class="navbar-item"  href="https://www.imanfattah.rocks/" target="_blank">
              Imanfattah.rocks&nbsp;&nbsp;<i class="fas fa-external-link-alt"></i>
            </a>                        -->
          </div>
        </div>        
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <span class="navbar-item">
              <a href="https://xabi.us/?add-to-cart=4291" class="button is-dark" target="_blank">
                <span class="pl-2">Pesan Buku</span>&nbsp;&nbsp;
              <i class="fas fa-external-link-alt"></i>                
              </a>
            </span>
          </div>
        </div>
      </div>
    </nav>
  </div>

  <div class="hero-body imn_hero">
    <div class="container">
      <div class="columns">
        <div class="column is-hidden-tablet">
          <div class="imn_foto_hero_home">
            <img src="~/static/img/iman_hero_book.jpg" />
          </div>
        </div>

        <div class="column">
      <h2 class="title imn_title">
        Iman Fattah
      </h2>
      <h3 class="subtitle imn_subtitle">
        Language and Ontology Engineer <span class="is-hidden-mobile">|</span> Musician and Audio Technologist <span class="is-hidden-mobile">|</span> Author
      </h3>

      <div class="imn_social">
        <a href="https://www.facebook.com/iman.fattah/" target="_blank">
              <i class="fab fa-facebook"></i>
        </a>
        <a href="https://instagram.com/imanfattah" target="_blank">
              <i class="fab fa-instagram"></i>
        </a>
        <a href="https://twitter.com/imanfattah" target="_blank">
              <i class="fab fa-twitter"></i>
        </a>
        <a href="https://www.linkedin.com/in/imanfattah/" target="_blank">
              <i class="fab fa-linkedin"></i>
        </a>
      </div>

      <div class="imn_cta_home_about buttons">
              <a href="/files/Resume_Iman_Fattah.pdf" class="button is-primary is-large" download>
                <span class="pl-2">Unduh Resume</span>&nbsp;&nbsp;<i class="fas fa-angle-double-down"></i>
              </a>

      </div>
        </div>
        <div class="column is-hidden-mobile">
          <div class="imn_foto_hero_home">
            <img src="~/static/img/iman_hero_book.jpg" />
          </div>
        </div>
      </div>



    </div>
  </div>

</section>
</template>
