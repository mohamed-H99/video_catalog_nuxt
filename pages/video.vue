<template>
  <div class="page-wrap mx-auto">
    <div class="position-relative">
      <!-- navbar -->
      <app-navbar />
      <div class="welcome-container fixed-header fixed-header-1">
        <div class="text-center">
          <p
            class="pt-5 px-3 welcome-text welcome-text-2 mb-1 text-white mx-auto"
          >
            Background image can be fixed. Content will simply slide over.
          </p>
        </div>
      </div>

      <!-- Header image -->
      <div id="fixed-header-bg"></div>
    </div>

    <!-- Page content -->
    <div class="container-fluid">
      <div class="mx-auto content-container">
        <main>
          <div class="row mb-5 pb-4">
            <div class="col-12">
              <!-- Video player 1422x800 -->
              <video width="1422" height="800" controls autoplay>
                <source src="~/assets/video/wheat-field.mp4" type="video/mp4" />
                Your browser does not support the video tag.
              </video>
            </div>
          </div>
          <div class="row mb-5 pb-5">
            <div class="col-xl-8 col-lg-7">
              <!-- Video description -->
              <div class="video-description-box">
                <h2 class="mb-5 video-title">
                  Mauris dapibus urna nec ipsum posuere
                </h2>
                <p class="mb-4">
                  Cras dictum pretium est, et imperdiet ex. Fusce vitae
                  vestibulum ipsum. Maecenas ultricies ipsum a urna ullamcorper,
                  id interdum est blandit. Vivamus sit amet justo sed erat
                  iaculis consequat. Nulla suscipit posuere lectus ut venenatis.
                  Proin sed orci eget tellus euismod vulputate eu eu arcu.
                </p>
                <p class="mb-4">
                  Etiam a bibendum lorem. Curabitur ac bibendum odio. Vivamus
                  euismod dui mauris, ut tincidunt mi congue quis. Phasellus
                  luctus orci dolor, a luctus massa tincidunt vitae. Integer sit
                  amet odio id libero tincidunt dignissim in eget arcu.
                </p>
                <p class="mb-4">
                  Aliquam tristique ut magna sit amet tincidunt. Sed tempor
                  tellus nulla, molestie luctus lectus tincidunt id. Cras
                  euismod leo a urna placerat, vel blandit turpis fermentum.
                </p>
              </div>
            </div>
            <div class="col-xl-4 col-lg-5">
              <!-- Share box -->
              <div class="bg-gray share-box">
                <h6 class="share-box-title mb-4">Share this video</h6>
                <div class="mb-5 d-flex">
                  <a href="" class="bg-white share-button"
                    ><i class="fab fa-facebook"></i
                  ></a>
                  <a href="" class="bg-white share-button"
                    ><i class="fab fa-twitter"></i
                  ></a>
                  <a href="" class="bg-white share-button"
                    ><i class="fab fa-pinterest"></i
                  ></a>
                  <a href="" class="bg-white share-button"
                    ><i class="far fa-envelope"></i
                  ></a>
                </div>
                <p class="mb-4">
                  Author:
                  <a href="https://github.com/mohamed-H99" class="text-link"
                    >ahmedhashem</a
                  >
                </p>
                <a
                  href="#"
                  class="bg-white px-5 mb-4 d-inline-block text-primary likes-box liked"
                >
                  <i class="fas fa-heart mr-3 liked-icon"></i>
                  <i class="far fa-heart mr-3 not-liked-icon"></i>
                  <span id="likes-count">486 likes</span>
                </a>
                <div>
                  <button
                    class="btn btn-primary p-0 btn-animate btn-download icon-download"
                  >
                    <span>Download Video</span>
                  </button>
                </div>
              </div>
            </div>
          </div>
          <div class="row pt-4 pb-5">
            <div class="col-12">
              <h2 class="mb-5 text-primary">Related Videos for You</h2>
              <div class="row catalog-item-list">
                <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
                  <div class="position-relative thumbnail-container">
                    <img
                      src="~/assets/img/tn-01.jpg"
                      alt="Image"
                      class="img-fluid catalog-item-img"
                    />
                    <nuxt-link
                      to="/video"
                      class="position-absolute img-overlay"
                    >
                      <i class="fas fa-play overlay-icon"></i>
                    </nuxt-link>
                  </div>
                  <div class="p-3 catalog-item-description">
                    <h3 class="text-gray text-center catalog-item-title">
                      Nam tincidunt consectetur
                    </h3>
                  </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
                  <div class="position-relative thumbnail-container">
                    <img
                      src="~/assets/img/tn-02.jpg"
                      alt="Image"
                      class="img-fluid catalog-item-img"
                    />
                    <nuxt-link
                      to="/video"
                      class="position-absolute img-overlay"
                    >
                      <i class="fas fa-play overlay-icon"></i>
                    </nuxt-link>
                  </div>
                  <div class="p-3 catalog-item-description">
                    <h3 class="text-gray text-center catalog-item-title">
                      Praesent posuere rhoncus
                    </h3>
                  </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
                  <div class="position-relative thumbnail-container">
                    <img
                      src="~/assets/img/tn-03.jpg"
                      alt="Image"
                      class="img-fluid catalog-item-img"
                    />
                    <nuxt-link
                      to="/video"
                      class="position-absolute img-overlay"
                    >
                      <i class="fas fa-play overlay-icon"></i>
                    </nuxt-link>
                  </div>
                  <div class="p-3 catalog-item-description">
                    <h3 class="text-gray text-center catalog-item-title">
                      Turpis massa aliquam
                    </h3>
                  </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
                  <div class="position-relative thumbnail-container">
                    <img
                      src="~/assets/img/tn-04.jpg"
                      alt="Image"
                      class="img-fluid catalog-item-img"
                    />
                    <nuxt-link
                      to="/video"
                      class="position-absolute img-overlay"
                    >
                      <i class="fas fa-play overlay-icon"></i>
                    </nuxt-link>
                  </div>
                  <div class="p-3 catalog-item-description">
                    <h3 class="text-gray text-center catalog-item-title">
                      Nam tincidunt consectetur
                    </h3>
                  </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
                  <div class="position-relative thumbnail-container">
                    <img
                      src="~/assets/img/tn-05.jpg"
                      alt="Image"
                      class="img-fluid catalog-item-img"
                    />
                    <nuxt-link
                      to="/video"
                      class="position-absolute img-overlay"
                    >
                      <i class="fas fa-play overlay-icon"></i>
                    </nuxt-link>
                  </div>
                  <div class="p-3 catalog-item-description">
                    <h3 class="text-gray text-center catalog-item-title">
                      Praesent posuere rhoncus
                    </h3>
                  </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 catalog-item">
                  <div class="position-relative thumbnail-container">
                    <img
                      src="~/assets/img/tn-06.jpg"
                      alt="Image"
                      class="img-fluid catalog-item-img"
                    />
                    <nuxt-link
                      to="/video"
                      class="position-absolute img-overlay"
                    >
                      <i class="fas fa-play overlay-icon"></i>
                    </nuxt-link>
                  </div>
                  <div class="p-3 catalog-item-description">
                    <h3 class="text-gray text-center catalog-item-title">
                      Turpis massa aliquam
                    </h3>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </main>
        <!-- footer -->
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style
AppFooter>
