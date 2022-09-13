<template>
    <nav class="navbar imn_bottomnav is-dark is-fixed-bottom is-hidden-tablet" role="navigation">
    <div class="navbar-brand">
        <nuxt-link to="/" class="navbar-item is-expanded is-block has-text-centered">
            <i class="fa fa-home"></i>
            <p class="is-size-7">Beranda</p>
        </nuxt-link>
        <nuxt-link to="/tour" class="navbar-item is-expanded is-block has-text-centered">
            <i class="fa fa-book"></i>
            <p class="is-size-7">Bedah Buku</p>
        </nuxt-link>
        <nuxt-link to="/credits" class="navbar-item is-expanded is-block has-text-centered">
            <i class="fa fa-info-circle"></i>
            <p class="is-size-7">Tentang Buku</p>
        </nuxt-link>
        <a href="https://xabi.us/?add-to-cart=4291" target="_blank" class="navbar-item is-expanded is-block has-text-centered">
            <i class="fa fa-shopping-cart"></i>
            <p class="is-size-7">Beli</p>
        </a>
    </div>
</nav>
</template>

<script>
export default {

}
</script>

<style>
</style>