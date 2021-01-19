<template>
  <div class="position-absolute site-header">
    <div class="container-fluid position-relative">
      <div class="row">
        <div class="col-7 col-md-4 video-icon">
          <nuxt-link to="/" class="bg-black text-center logo-container">
            <i class="fas fa-video site-logo mb-3"></i>
            <h1 class="site-name">Video Catalog</h1>
          </nuxt-link>
        </div>
        <div class="col-5 col-md-8 ml-auto mr-0">
          <div class="site-nav">
            <nav class="navbar navbar-expand-lg mr-0 ml-auto" id="main-nav">
              <button
                class="navbar-toggler bg-black py-2 px-3 mr-0 ml-auto"
                type="button"
                data-toggle="collapse"
                data-target="#navbar-nav"
                aria-controls="navbar-nav"
                :aria-expanded="{'false': show}"
                aria-label="Toggle navigation"
                @click="show = !show"
                :class="{'collapsed': !show}"
              >
                <span>
                  <i class="fas fa-bars menu-closed-icon"></i>
                  <i class="fas fa-times menu-opened-icon"></i>
                </span>
              </button>
              <div class="collapse navbar-collapse nav" :class="{'show': show}" id="navbar-nav">
                <ul class="navbar-nav text-uppercase">
                  <nuxt-link to="/" tag="li" exact-active-class="active" class="nav-item">
                    <a class="nav-link nav-link" href="#"
                      >Videos <span class="sr-only">(current)</span></a
                    >
                  </nuxt-link>
                  <nuxt-link to="/about" tag="li" exact-active-class="active" class="nav-item">
                    <a class="nav-link nav-link" href="#">About</a>
                  </nuxt-link>
                  <nuxt-link to="/contact" tag="li" exact-active-class="active" class="nav-item">
                    <a class="nav-link nav-link" href="#">Contact</a>
                  </nuxt-link>
                </ul>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppNavbar",
  data: function() {
    return {
      show: false
    }
  }
}
</script>

<style>
@media (max-width: 576px) {
  .video-icon {
    display: none;
  }
}

</style>