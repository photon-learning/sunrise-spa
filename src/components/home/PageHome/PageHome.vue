<script src="./PageHome.js"></script>
<style src="./PageHome.scss" lang="scss"></style>

<template>
<span>
  <Banner />

  <div class="banner-area pt-30">
    <div class="custom-container">
      <div class="row">
        <div class="col-lg-4 col-md-4 col-xs-12">
          <div
            class="banner-wrap mb-30 wow fadeIn"
            data-wow-duration="1s"
            data-wow-delay="0.2s"
          >
            <div class="banner-img banner-hover banner-zoom">
              <router-link
                :to="{ name: 'products', params: { categorySlug: 'Sneakers' } }"
              >
                <img src="assets/img/jeans1.jpg" alt="banner" />
                <div class="banner-content">
                  <h3>WOMAN SNEAKERS</h3>
                </div>
              </router-link>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-4 col-xs-12">
          <div
            class="banner-wrap mb-30 wow fadeIn"
            data-wow-duration="1s"
            data-wow-delay="0.2s"
          >
            <div class="banner-img banner-hover banner-zoom">
              <router-link
                :to="{ name: 'products', params: { categorySlug: 'running' } }"
              >
                <img src="assets/img/sho3.jpg" alt="banner" />
                <div class="banner-content">
                  <h3>MAN RUNNING SHOES</h3>
                </div>
              </router-link>
            </div>
          </div>
          <div
            class="banner-wrap mb-30 wow fadeIn"
            data-wow-duration="1s"
            data-wow-delay="0.3s"
          >
            <div class="banner-img banner-hover banner-zoom">
              <router-link
                :to="{ name: 'products', params: { categorySlug: 'man-soccer' } }"
              >
                <img src="assets/img/acc.jpg" alt="banner" />
                <div class="banner-content">
                  <h3>SOCCER</h3>
                </div>
              </router-link>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-4 col-xs-12">
          <div
            class="banner-wrap mb-30 wow fadeIn"
            data-wow-duration="1s"
            data-wow-delay="0.2s"
          >
            <div class="banner-img banner-hover banner-zoom">
              <router-link
                :to="{ name: 'products', params: { categorySlug: 'kids' } }"
              >
                <img src="assets/img/s3.jpg" alt="banner" />
                <div class="banner-content">
                  <h3>KIDS SHOES</h3>
                </div>
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="service-area pt-70 pb-70">
    <div class="container">
      <div class="row">
        <div class="col-lg-3 col-md-6 col-sm-6">
          <div class="service-wrap mb-30 wow fadeInUp" data-wow-delay="0.1s">
            <div class="service-icon">
              <i class="las la-shipping-fast"></i>
            </div>
            <div class="service-content">
              <h6>Free Worldwide Shipping</h6>
              <p>
                On all orders over {{ $store.state.country === 'DE' ? '€' : '$'
                }}100
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-6">
          <div class="service-wrap mb-30 wow fadeInUp" data-wow-delay="0.2s">
            <div class="service-icon">
              <i class="las la-coins"></i>
            </div>
            <div class="service-content">
              <h6>30 Days Money Returns</h6>
              <p>30 days money back guarantee</p>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-6">
          <div class="service-wrap mb-30 wow fadeInUp" data-wow-delay="0.3s">
            <div class="service-icon">
              <i class="las la-headphones"></i>
            </div>
            <div class="service-content">
              <h6>Support 24/7</h6>
              <p>Offered in the country of usage</p>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-6">
          <div class="service-wrap mb-30 wow fadeInUp" data-wow-delay="0.4s">
            <div class="service-icon">
              <i class="las la-shield-alt"></i>
            </div>
            <div class="service-content">
              <h6>100% Secure Checkout</h6>
              <p>Paypal / Visa / Master Card</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</span>

</template>
