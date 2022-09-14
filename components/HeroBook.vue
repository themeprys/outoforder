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
              <a class="navbar-item" href="#synopsys">
                Synopsys
              </a>
              <!-- <nuxt-link class="navbar-item" to="/tour">
              Bedah Buku
            </nuxt-link> -->
              <a class="navbar-item" href="#aboutwriter">
                About the Writer
              </a>
              <a class="navbar-item" href="#ordernow">Order Now</a>

              <!-- <a class="navbar-item"  href="https://www.imanfattah.rocks/" target="_blank">
              Imanfattah.rocks&nbsp;&nbsp;<i class="fas fa-external-link-alt"></i>
            </a> -->
            </div>
          </div>
          <div id="navbarMenuHeroB" class="navbar-menu">
            <div class="navbar-end">
              <span class="navbar-item">
                <a
                  href="#"
                  class="button is-dark"
                  target="_blank"
                >
                  <span class="pl-2">Contact Us</span>&nbsp;&nbsp;
                  <i class="fas fa-envelope"></i>
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
              Book 1: Out of Order
            </h3>
            <div class="imn_book_text">
              <p>OUT OF ORDER, the first novel in the coming series The tales of the Urban misfits is a coming-of-age fiction inspired by a true story.</p>
              <p>Written by <strong>Meita Kasim</strong><br>
              Editing by <strong>Dr. Margie Ellery</strong><br>
              Cover Design by <strong>Anggito Rahman</strong></p>
              <p>Printed and bound by <strong>Arung Wacana</strong>, Yogyakarta.<br>First published in Indonesia 2022</p>
              <!-- <p>It follows the life of Sigi, a girl in her late teens living in Jakarta during the 1990s, in a nation with its Muslim majority and strong military presence</p>
              <p>While still a high school student, Sigi plays in an all-girl alternative band and she broadcast at a radio station, yet, as a young Muslim woman, her passions evoke judgement and harassment.</p>
              <p>Shadowed by her controlling mother, she yearns to be a free spirit amidst increasing controversy in the male dominated underground and in herself.</p>
              <p>Despite these obstacle, Sigi courageously follows her own path and defies all the constructs of her time to find her true and unique voice; a choice that is often painful, inspiring, and, ultimately, one full of hope.</p> -->
            </div>

            <div class="imn_cta_book buttons">
              <a class="button is-dark is-medium" href="#" target="_blank">
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
