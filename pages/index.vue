<template>
  <div class="page-wrap mx-auto">
    <div class="position-relative">
      <!-- navbar -->
      <app-navbar />
      <div class="welcome-container text-center text-white">
        <div class="welcome-container-inner">
          <p class="welcome-text mb-1 text-white">
            Video Catalog is brought to you by our Company.
          </p>
          <p class="welcome-text mb-5 text-white">
            This is a full-width video banner.
          </p>
          <a href="#content" class="btn btn-animate btn-cta icon-down">
            <span>Discover</span>
          </a>
        </div>
      </div>

      <div id="video-container">
        <video autoplay muted loop id="video">
          <!-- <source src="~/assets/video/sunset-timelapse-video.mp4" type="video/mp4"> -->
          <source src="~/assets/video/wheat-field.mp4" type="video/mp4" />
        </video>
      </div>

      <i id="video-control-button" class="fas fa-pause"></i>
    </div>

    <div class="container-fluid">
      <div id="content" class="mx-auto content-container">
        <main>
          <div class="row">
            <div class="col-12">
              <h2 class="page-title mb-4">Our Video Catalog</h2>
              <div class="categories-container mb-5">
                <h3 class="text-primary categories-text">Categories:</h3>
                <ul class="nav category-list">
                  <li class="nav-item category-item">
                    <a href="#" class="nav-link category-link active">All</a>
                  </li>
                  <li class="nav-item category-item">
                    <a href="#" class="nav-link category-link">Drone Shots</a>
                  </li>
                  <li class="nav-item category-item">
                    <a href="#" class="nav-link category-link">Nature</a>
                  </li>
                  <li class="nav-item category-item">
                    <a href="#" class="nav-link category-link">Actions</a>
                  </li>
                  <li class="nav-item category-item">
                    <a href="#" class="nav-link category-link">Featured</a>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <div class="row catalog-item-list">
            <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
              <div class="position-relative thumbnail-container">
                <img
                  src="~/assets/img/tn-01.jpg"
                  alt="Image"
                  class="img-fluid catalog-item-img"
                />
                <nuxt-link to="/video" class="position-absolute img-overlay">
                  <i class="fas fa-play overlay-icon"></i>
                </nuxt-link>
              </div>
              <div class="p-4 bg-gray catalog-item-description">
                <h3 class="text-primary mb-3 catalog-item-title">
                  Aenean aliquet sapien
                </h3>
                <p class="catalog-item-text">
                  Video thumbnail has a link to another HTML page. Categories
                  <span class="text-secondary">do not need</span> any JS. They
                  are just separated HTML pages. Paging is at the bottom to
                  extend the list as long as you want. This can be a large
                  catalog.
                </p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
              <div class="position-relative thumbnail-container">
                <img
                  src="~/assets/img/tn-02.jpg"
                  alt="Image"
                  class="img-fluid catalog-item-img"
                />
                <nuxt-link to="/video" class="position-absolute img-overlay">
                  <i class="fas fa-play overlay-icon"></i>
                </nuxt-link>
              </div>
              <div class="p-4 bg-gray catalog-item-description">
                <h3 class="text-primary mb-3 catalog-item-title">
                  Mauris in odio vel odio
                </h3>
                <p class="catalog-item-text">
                  You may need to contact us for a quick chat or send an email
                  if you have any question about this CSS template.
                  <span class="text-secondary"
                    >font-family: 'Source Sans Pro', sans-serif; for this
                    template.</span
                  >
                </p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
              <div class="position-relative thumbnail-container">
                <img
                  src="~/assets/img/tn-03.jpg"
                  alt="Image"
                  class="img-fluid catalog-item-img"
                />
                <nuxt-link to="/video" class="position-absolute img-overlay">
                  <i class="fas fa-play overlay-icon"></i>
                </nuxt-link>
              </div>
              <div class="p-4 bg-gray catalog-item-description">
                <h3 class="text-primary mb-3 catalog-item-title">
                  Sagittis sodales enim
                </h3>
                <p class="catalog-item-text">
                  You are allowed to use this video catalog for your business
                  websites. Please do not make a re-distribution of our template
                  ZIP file on any template collection website.
                </p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
              <div class="position-relative thumbnail-container">
                <img
                  src="~/assets/img/tn-04.jpg"
                  alt="Image"
                  class="img-fluid catalog-item-img"
                />
                <nuxt-link to="/video" class="position-absolute img-overlay">
                  <i class="fas fa-play overlay-icon"></i>
                </nuxt-link>
              </div>
              <div class="p-4 bg-gray catalog-item-description">
                <h3 class="text-primary mb-3 catalog-item-title">
                  Nam tincidunt consectetur
                </h3>
                <p class="catalog-item-text">
                  You can apply this template for your commercial CMS theme. Nam
                  sem leo, imperdiet non lacinia eget, volutpat ac massa. Donec
                  mattis in velit quis commodo. Cras nec rutrum arcu.
                </p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
              <div class="position-relative thumbnail-container">
                <img
                  src="~/assets/img/tn-05.jpg"
                  alt="Image"
                  class="img-fluid catalog-item-img"
                />
                <nuxt-link to="/video" class="position-absolute img-overlay">
                  <i class="fas fa-play overlay-icon"></i>
                </nuxt-link>
              </div>
              <div class="p-4 bg-gray catalog-item-description">
                <h3 class="text-primary mb-3 catalog-item-title">
                  Praesent posuere rhoncus
                </h3>
                <p class="catalog-item-text">
                  Duis vulputate nisl metus, eget dapibus nunc ultricies id. Ut
                  augue mauris, varius quis nulla non, sollicitudin consectetur
                  nisl. Donec eget arcu placerat, ullamcorper.
                </p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
              <div class="position-relative thumbnail-container">
                <img
                  src="~/assets/img/tn-06.jpg"
                  alt="Image"
                  class="img-fluid catalog-item-img"
                />
                <nuxt-link to="/video" class="position-absolute img-overlay">
                  <i class="fas fa-play overlay-icon"></i>
                </nuxt-link>
              </div>
              <div class="p-4 bg-gray catalog-item-description">
                <h3 class="text-primary mb-3 catalog-item-title">
                  Turpis massa aliquam
                </h3>
                <p class="catalog-item-text">
                  Nunc neque risus, ultrices sed luctus at, iaculis at arcu.
                  Pellentesque rutrum velit nec sapien ullamcorper ultrices.
                  Vestibulum lectus risus, laoreet pretium ipsum
                </p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
              <div class="position-relative thumbnail-container">
                <img
                  src="~/assets/img/tn-07.jpg"
                  alt="Image"
                  class="img-fluid catalog-item-img"
                />
                <nuxt-link to="/video" class="position-absolute img-overlay">
                  <i class="fas fa-play overlay-icon"></i>
                </nuxt-link>
              </div>
              <div class="p-4 bg-gray catalog-item-description">
                <h3 class="text-primary mb-3 catalog-item-title">
                  Class aptent taciti sociosqu
                </h3>
                <p class="catalog-item-text">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Phasellus bibendum orci sit amet dignissim rhoncus.
                  Pellentesque pretium faucibus vestibulum.
                </p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
              <div class="position-relative thumbnail-container">
                <img
                  src="~/assets/img/tn-08.jpg"
                  alt="Image"
                  class="img-fluid catalog-item-img"
                />
                <nuxt-link to="/video" class="position-absolute img-overlay">
                  <i class="fas fa-play overlay-icon"></i>
                </nuxt-link>
              </div>
              <div class="p-4 bg-gray catalog-item-description">
                <h3 class="text-primary mb-3 catalog-item-title">
                  Donec ac nisl ul elit
                </h3>
                <p class="catalog-item-text">
                  Suspendisse in odio congue, lobortis metus sed, venenatis
                  nisl. In dapibus et massa feugiat facilisis. Maecenas
                  venenatis aliquet nulla, a tincidunt erat suscipit eget.
                </p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
              <div class="position-relative thumbnail-container">
                <img
                  src="~/assets/img/tn-09.jpg"
                  alt="Image"
                  class="img-fluid catalog-item-img"
                />
                <nuxt-link to="/video" class="position-absolute img-overlay">
                  <i class="fas fa-play overlay-icon"></i>
                </nuxt-link>
              </div>
              <div class="p-4 bg-gray catalog-item-description">
                <h3 class="text-primary mb-3 catalog-item-title">
                  Sed mattis nisi erat
                </h3>
                <p class="catalog-item-text">
                  Integer ultricies mi eu aliquet cursus. Nam sem leo, imperdiet
                  non lacinia eget, volutpat ac massa. Donec mattis in velit
                  quis commodo. Cras nec rutrum arcu.
                </p>
              </div>
            </div>
          </div>

          <!-- Catalog Paging Buttons -->
          <div>
            <ul class="nav paging-links">
              <li class="nav-item active">
                <a href="#" class="nav-link paging-link">1</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link paging-link">2</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link paging-link">3</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link paging-link">4</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link paging-link">></a>
              </li>
            </ul>
          </div>
        </main>
        <!-- footer -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'index',
}
</script>

<style>
.parallax-window img {
  width: 100%;
  max-height: 360px;
  object-fit: cover;
}
</style>
