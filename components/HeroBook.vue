<template>
  <section class="hero is-large">
    <div class="hero-head">
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <nuxt-link to="/" class="navbar-item">
              The Tales of<br />the Urban Misfits
              <!-- <img src="~/static/img/outoforder_logojpg" alt="Iman Fattah" height="100px"> -->
            </nuxt-link>
            <div class="mt-5 navbar-burger">
              <nuxt-link to="/about">
                My Profile <i class="fas fa-user"></i>
              </nuxt-link>
            </div>
          </div>
          <div id="navbarMenuHeroB" class="navbar-menu">
            <div class="navbar-end">
              <nuxt-link to="/" class="navbar-item is-active"> Home </nuxt-link>
              <nuxt-link class="navbar-item" to="/credits">
                About Book
              </nuxt-link>
              <!-- <nuxt-link class="navbar-item" to="/tour">
              Bedah Buku
            </nuxt-link> -->
              <nuxt-link class="navbar-item" to="/about">
                About Writer
              </nuxt-link>
              <nuxt-link class="navbar-item" to="/contact"> Contact </nuxt-link>

              <!-- <a class="navbar-item"  href="https://www.imanfattah.rocks/" target="_blank">
              Imanfattah.rocks&nbsp;&nbsp;<i class="fas fa-external-link-alt"></i>
            </a> -->
            </div>
          </div>
          <div id="navbarMenuHeroB" class="navbar-menu">
            <div class="navbar-end">
              <span class="navbar-item">
                <a
                  href="https://xabi.us/?add-to-cart=4291"
                  class="button is-dark"
                  target="_blank"
                >
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
          <div class="column is-4">
            <div class="imn_foto_hero_home">
              <img src="~/static/img/outoforder_cover.webp" class="img-fluid" />
            </div>
          </div>
          <div class="column details">
            <h2 class="title imn_book_title">The Tales of the Urban Misfits</h2>
            <h3 class="subtitle imn_book_subtitle">
              a fiction novel by Meita Kasim
            </h3>
            <div class="imn_book_text">
              <p>Book 1: Out of Order</p>
              <p>First published in 2021</p>
              <!-- <p>It follows the life of Sigi, a girl in her late teens living in Jakarta during the 1990s, in a nation with its Muslim majority and strong military presence</p>
              <p>While still a high school student, Sigi plays in an all-girl alternative band and she broadcast at a radio station, yet, as a young Muslim woman, her passions evoke judgement and harassment.</p>
              <p>Shadowed by her controlling mother, she yearns to be a free spirit amidst increasing controversy in the male dominated underground and in herself.</p>
              <p>Despite these obstacle, Sigi courageously follows her own path and defies all the constructs of her time to find her true and unique voice; a choice that is often painful, inspiring, and, ultimately, one full of hope.</p> -->
            </div>

            <div class="imn_cta_book buttons">
              <a class="button is-warning is-medium" href="#" target="_blank">
                Buy Printed Edition
              </a>
              <a class="button is-primary is-medium" href="#" target="_blank">
                Buy E-book on Amazon
              </a>
            </div>

          </div>
        </div>
      </div>
    </div>
  </section>
</template>
