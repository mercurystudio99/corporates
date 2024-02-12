<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div>
    <div class="position-relative">
      <div class="bg-image px-4 position-relative d-flex align-items-center"
        style="background-image: url('assets/images/hero.png'); background-size: cover; background-position: bottom; height: 100vh;">
        <div class="col-lg-6" style="z-index: 3">
          <h2 class="display-5 fw-bold lh-1 mb-3 text-white lh-sm">Rewards program<br /> for corporates'<br /> employees</h2>
          <div class="d-grid gap-2 d-md-flex justify-content-md-start">
            <button type="button" class="btn btn-primary btn-lg px-4 me-md-2 rounded-pill">Get a demo</button>
          </div>
        </div>
        <div class="position-absolute bottom-0" style="right:8%">
          <img width="700px" src="../../public/assets/images/service.png" class="d-block " loading="lazy">
        </div>
      </div>
    </div>

    <!-- offers section -->
    <section>
      <div class="position-relative">
        <h4 class="text-center my-4">Exclusive offers for your employees</h4>
        <!-- Carousel -->
        <div class="slider">
          <div class="slide-track">
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (1).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (2).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (3).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (4).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (5).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (6).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (7).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (8).png" />
            </div>
            <!-- same slides doubled (duplicate) -->
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (1).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (2).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (3).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (4).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (5).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (6).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (7).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_offer (8).png" />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- program service section -->
    <section class="py-3 py-md-5 position-relative">
      <div class="position-absolute bg-image w-75 h-75 bottom-0" style="background-image: url('assets/images/bg_program.png'); background-size: contain; background-repeat: no-repeat;"></div>
      <div class="position-relative">

        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
              <h2 class="mb-4 display-5 text-center">Corporate program services</h2>
            </div>
          </div>
        </div>

        <div class="container overflow-hidden">
          <div class="row gx-4 gy-2">
            <div class="col-6 align-self-center">
              <div class="border border-1 rounded-4 p-2">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_infinite_dark.png" width="50" height="50" />
                  <span>Unlimited access to offers for all employees and their families</span>
                </div>
              </div>
            </div>

            <div class="col-6 align-self-center">
              <div class="border border-1 rounded-4 p-2">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_gift_dark.png" width="50" height="50" />
                  <span>Purchasing and delivering gifts to the employees</span>
                </div>
              </div>
            </div>

            <div class="col-6 align-self-center">
              <div class="border border-1 rounded-4 p-2">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_wallet_dark.png" width="50" height="50" />
                  <span>Top up wallet for employees to buy gifts</span>
                </div>
              </div>
            </div>

            <div class="col-6 align-self-center">
              <div class="border border-1 rounded-4 p-2">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_tool_dark.png" width="50" height="50" />
                  <span>Customer service to ensure your employees' satisfaction</span>
                </div>
              </div>
            </div>

            <div class="col-6 align-self-center">
              <div class="border border-1 rounded-4 p-2">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_congrat_dark.png" width="50" height="50" />
                  <span>Manage internal events</span>
                </div>
              </div>
            </div>

            <div class="col-6 align-self-center">
              <div class="border border-1 rounded-4 p-2">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_upload_dark.png" width="50" height="50" />
                  <span>Onboarding brands by the company’s request</span>
                </div>
              </div>
            </div>

          </div>
        </div>

      </div>
    </section>

    <!-- mobile app section -->
    <section>
      <div class="container">
        <div class="row justify-content-md-center">
          <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
            <h2 class="mb-4 display-5 text-center">App with your company identity</h2>
          </div>
        </div>
      </div>

      <div class="d-flex overflow-auto px-4">
        <div class="mx-4">
          <img src="../../public/assets/images/phone1.png" height="500"/>
        </div>
        <div class="mx-4">
          <img src="../../public/assets/images/phone2.png" height="500"/>
        </div>
        <div class="mx-4">
          <img src="../../public/assets/images/phone3.png" height="500"/>
        </div>
        <div class="mx-4">
          <img src="../../public/assets/images/phone4.png" height="500"/>
        </div>
        <div class="mx-4">
          <img src="../../public/assets/images/phone5.png" height="500"/>
        </div>
      </div>
    </section>

    <!-- companies section -->
    <section>
      <div class="position-relative">
        <h4 class="text-center my-4">Companies that trust us</h4>
        <!-- Carousel -->
        <div class="slider">
          <div class="slide-track">
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (1).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (2).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (3).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (4).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (5).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (6).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (7).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (8).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (9).png" />
            </div>
            <!-- same slides doubled (duplicate) -->
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (1).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (2).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (3).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (4).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (5).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (6).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (7).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (8).png" />
            </div>
            <div class="slide-item">
              <img src="../../public/assets/images/icon_company (9).png" />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- features section -->
    <section class="position-relative">
      <img src="../../public/assets/images/bg_feature.png" class="position-absolute end-0"/>
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
              <h2 class="my-4 display-5 text-center">App Features</h2>
            </div>
          </div>
        </div>

        <div id="carouselFeatureIndicators" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-indicators">
            <div data-bs-target="#carouselFeatureIndicators" data-bs-slide-to="0" class="active rounded-circle" aria-current="true" aria-label="Slide 1"></div>
            <div data-bs-target="#carouselFeatureIndicators" data-bs-slide-to="1" class="rounded-circle" aria-label="Slide 2"></div>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <div style="height: 300px;">
                <div class="container">
                  <div class="row">
                    <div class="col">
                      <div class="mx-auto w-50">
                        <div class="bg-dark rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_infinite_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Unlimited Discounts and offers</h5>
                      </div>
                    </div>
                    <div class="col">
                      <div class="mx-auto w-50">
                        <div class="bg-dark rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_phone_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Brands information</h5>
                      </div>
                    </div>
                    <div class="col">
                      <div class="mx-auto w-50">
                        <div class="bg-dark rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_clock_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Track your savings</h5>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="carousel-item">
              <div style="height: 300px;">
                <div class="container">
                  <div class="row">
                    <div class="col">
                      <div class="mx-auto w-50">
                        <div class="bg-dark rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_clock_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Track your savings</h5>
                      </div>
                    </div>
                    <div class="col">
                      <div class="mx-auto w-50">
                        <div class="bg-dark rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_wallet_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Discounts, Guaranteed</h5>
                      </div>
                    </div>
                    <div class="col">
                      <div class="mx-auto w-50">
                        <div class="bg-dark rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_star_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Points on every transaction</h5>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </section>

    <!-- features section -->
    <section>
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
              <h2 class="my-4 display-5 text-center">Previous Events</h2>
            </div>
          </div>
        </div>

        <div id="carouselEventIndicators" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <div class="w-75 mx-auto rounded-4" style="min-height: 300px; background: linear-gradient(45deg, #2424FF, #1B0C75);">

                <div class="container col-xxl-8 px-4 py-5">
                  <div class="row flex-lg-row-reverse align-items-center g-5 py-1">
                    <div class="col-10 col-sm-8 col-lg-6">
                      <div class="w-80 mx-auto rounded-4 bg-dark" style="height: 200px;"></div>
                    </div>
                    <div class="col-lg-6">
                      <h1 class="display-5 fw-bold lh-1 mb-3 text-white">SPL</h1>
                      <p class="lead text-white">The stories about what they love about our services.</p>
                    </div>
                  </div>
                </div>

              </div>
            </div>

            <div class="carousel-item">
              <div class="w-75 mx-auto rounded-4" style="min-height: 300px; background: linear-gradient(45deg, #2424FF, #1B0C75);">


                <div class="container col-xxl-8 px-4 py-5">
                  <div class="row flex-lg-row-reverse align-items-center g-5 py-1">
                    <div class="col-10 col-sm-8 col-lg-6">
                      <div class="w-80 mx-auto rounded-4 bg-dark" style="height: 200px;"></div>
                    </div>
                    <div class="col-lg-6">
                      <h1 class="display-5 fw-bold lh-1 mb-3 text-white">SPL</h1>
                      <p class="lead text-white">The stories about what they love about our services.</p>
                    </div>
                  </div>
                </div>

              </div>
            </div>

          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselEventIndicators" data-bs-slide="prev">
            <img src="../../public/assets/images/arrow_left.png"/>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselEventIndicators" data-bs-slide="next">
            <img src="../../public/assets/images/arrow_right.png"/>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </section>

</div>
</template>

<style scoped>
.slider {
  position: relative;
  width: 100%;

  display: grid;
  place-items: center;
  overflow: hidden;
}
.slider::before,
.slider::after{
  position:absolute;
  background-image:linear-gradient(to right,rgba(255,255,255,1) 0%,rgba(255,255,255,0) 100%);
  content:'';
  height:100%;width:25%;
  z-index:2;pointer-events:none;
}
.slider::before{
  left:0;
  top:0;
}
.slider::after{
  right:0;
  top:0;
  transform:rotateZ(180deg);
}

.slide-track {
  width: calc(150px * 20);
  height: 200px;
  display: flex;
  animation: scroll 20s linear infinite;
  justify-content: space-between;
}

.slide-item {
  width: 150px;
  display: grid;
  place-items: center;
  transition:0.5s;
  cursor:pointer;
}
.slide-item:hover{
  transform:scale(0.8)
}

@keyframes scroll {
  0% {
    transform: translateX(0px);
  }
  100% {
    transform: translateX(calc(-150px * 10));
  }
}

@media screen and (max-width: 768px) {
  .slide-track {
    width: calc(80px * 20);
  }
  .slide-item {
    width: 80px;
  }
  @keyframes scroll {
    0% {
      transform: translateX(0px);
    }
    100% {
      transform: translateX(calc(-80px * 10));
    }
  }
}

.carousel-indicators [data-bs-target] {
  width: 20px; height: 20px;
  background-color: gray;
}
.carousel-indicators .active {
  background-color: orange;
}
</style>
