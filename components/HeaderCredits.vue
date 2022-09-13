<template>
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <nuxt-link to="/" class="navbar-item">
            <img src="~/static/img/iman_logo.svg" alt="Iman Fattah" height="100px">
          </nuxt-link>
          <div class="mt-5 navbar-burger">
          <!-- <a href="/files/Resume_Iman_Fattah.pdf" download>
                Pesan Buku <i class="fas fa-download"></i>
          </a> -->
          </div>
        </div>
        <div id="navbarImn" class="navbar-menu">
          <div class="navbar-end">
            <nuxt-link class="navbar-item" to="/">
              Rupa Suara
            </nuxt-link>
            <nuxt-link class="navbar-item is-active" to="/credits">
              Tentang Buku
            </nuxt-link>
            <nuxt-link class="navbar-item" to="/tour">
              Bedah Buku
            </nuxt-link>
            <nuxt-link class="navbar-item" to="/about">
              Tentang Saya
            </nuxt-link>
            <nuxt-link class="navbar-item"  to="/contact">
              Kontak
            </nuxt-link>

            <!-- <a class="navbar-item"  href="https://www.imanfattah.rocks/" target="_blank">
              Imanfattah.rocks&nbsp;&nbsp;<i class="fas fa-external-link-alt"></i>
            </a>                       
             -->
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
</template>
