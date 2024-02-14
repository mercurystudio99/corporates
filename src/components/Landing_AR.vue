<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <!-- Modal -->
  <div class="modal fade" id="exampleModal" tabindex="-1" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-body">
          <div class="d-flex justify-content-between align-items-center">
            <h5 class="modal-title">Success submitted!</h5>
            <button class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div>
    <!-- hero section -->
    <section>
      <div class="position-relative">
        <div class="bg-image px-4 position-relative hero"
          style="background-image: url('assets/images/hero_ar.png'); background-size: cover; background-position: bottom;">
          <div class="d-flex justify-content-between align-items-center mx-10">
            <a href="#"><img src="../../public/assets/images/logo.png"/></a>
            <div class="dropdown">
              <a class="text-decoration-none" href="#" role="button" id="dropdownMenuLink" data-bs-toggle="dropdown" aria-expanded="false">
                <span class="mx-2 text-white">Arabic</span><img src="../../public/assets/images/flag_ar.png"/>
              </a>
              <ul class="dropdown-menu" aria-labelledby="dropdownMenuLink">
                <li><a class="dropdown-item" href="#">Arabic</a></li>
                <li><a class="dropdown-item" href="#">English</a></li>
              </ul>
            </div>
          </div>
          <div class="hero-title-margin">
            <div class="col-12 col-md-7 col-lg-6 px-4" style="z-index: 3">
              <h2 class="hero-title fw-bold lh-1 mb-3 text-white lh-sm">برنامج مكافآت <br /> الموظفين والعملاء</h2>
              <div class="d-grid gap-2 d-flex justify-content-center justify-content-md-start my-4">
                <a href="#partnershipform" class="btn btn-primary btn-lg px-4 me-md-2 rounded-pill bg-secondary-normal border-0">عرض تجريبي</a>
              </div>
            </div>
          </div>
          <div class="hero-image bottom-0">
            <img width="100%" height="100%" src="../../public/assets/images/service_ar.png" class="d-block " loading="lazy">
          </div>
        </div>
      </div>
    </section>

    <!-- offers section -->
    <section>
      <div class="position-relative my-100">
        <h2 class="my-4 display-5 text-center text-primary-thick fw-bold">أبرز العلامات التجارية</h2>
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
      <div class="position-absolute bg-image w-75 h-75 bottom-0 start-0" style="background-image: url('assets/images/bg_program.png'); background-size: contain; background-repeat: no-repeat;"></div>
      <div class="position-relative">

        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold">خدمات برنامج الشركات</h2>
            </div>
          </div>
        </div>

        <div class="container overflow-hidden">
          <div class="row gx-4 gy-2 m-4">
            <div class="col-12 col-md-6">
              <div class="border border-1 border-primary-thick rounded-4 p-2 bg-white">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_infinite_dark.png" width="50" height="50" />
                  <span class="mx-2">عروض لجميع موظفي الشركة وأفراد أسرهم</span>
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6">
              <div class="border border-1 border-primary-thick rounded-4 p-2 bg-white">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_gift_dark.png" width="50" height="50" />
                  <span class="mx-2">شراء وتوصيل الهدايا للموظفين</span>
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6">
              <div class="border border-1 border-primary-thick rounded-4 p-2 bg-white">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_wallet_dark.png" width="50" height="50" />
                  <span class="mx-2">شحن رصيد الموظف لشراء هدايا</span>
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6">
              <div class="border border-1 border-primary-thick rounded-4 p-2 bg-white">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_tool_dark.png" width="50" height="50" />
                  <span class="mx-2">خدمة عملاء لضمان رضا  الموظفين</span>
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6">
              <div class="border border-1 border-primary-thick rounded-4 p-2 bg-white">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_congrat_dark.png" width="50" height="50" />
                  <span class="mx-2">تنظيم الفعاليات الداخلية الخاصة بالشركة</span>
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6">
              <div class="border border-1 border-primary-thick rounded-4 p-2 bg-white">
                <div class="d-flex justify-content-start align-items-center">
                  <img src="../../public/assets/images/icon_upload_dark.png" width="50" height="50" />
                  <span class="mx-2">إضافة عروض  بناء على طلب الشركة</span>
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
          <div class="col-12">
            <h2 class="my-4 display-5 text-center text-primary-thick fw-bold">تطبيق يعكس هوية شركتك</h2>
          </div>
        </div>
      </div>

      <div class="d-flex overflow-auto px-4 my-4">
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
    <section class="my-100">
      <div class="position-relative">
        <h2 class="my-4 display-5 text-center text-primary-thick fw-bold">شركاء يقدمون مزايا SDC App لموظفيهم</h2>
        <!-- Carousel -->
        <div class="slider">
          <div class="slide-track2">
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
      <img src="../../public/assets/images/bg_feature.png" class="position-absolute end-0 feature-bg"/>
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold">مزايا التطبيق</h2>
            </div>
          </div>
        </div>

        <div id="carouselFeatureIndicators" class="carousel slide my-4" data-bs-ride="carousel">
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
                      <div class="mx-auto feature-card">
                        <div class="bg-primary-thick rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_infinite_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Unlimited Discounts and offers</h5>
                      </div>
                    </div>
                    <div class="col">
                      <div class="mx-auto feature-card">
                        <div class="bg-primary-normal rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_phone_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Brands information</h5>
                      </div>
                    </div>
                    <div class="col">
                      <div class="mx-auto feature-card">
                        <div class="bg-primary-thin rounded-4 p-4 mx-4">
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
                      <div class="mx-auto feature-card">
                        <div class="bg-primary-thin rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_clock_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Track your savings</h5>
                      </div>
                    </div>
                    <div class="col">
                      <div class="mx-auto feature-card">
                        <div class="bg-primary-thick rounded-4 p-4 mx-4">
                            <img src="../../public/assets/images/icon_wallet_light.png" width="100%" height="100%" />
                        </div>
                        <h5 class="text-center my-4">Discounts, Guaranteed</h5>
                      </div>
                    </div>
                    <div class="col">
                      <div class="mx-auto feature-card">
                        <div class="bg-primary-normal rounded-4 p-4 mx-4">
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

    <!-- event section -->
    <section class="my-100">
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold">فعاليات سابقة</h2>
            </div>
          </div>
        </div>

        <div id="carouselEventIndicators" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <div class="w-75 mx-auto rounded-4" style="min-height: 300px; background: linear-gradient(45deg, #2424FF, #1B0C75);">

                <div class="container p-5">
                  <div class="row flex-lg-row align-items-center g-2 g-lg-5 py-1">
                    <div class="col-12 col-lg-5">
                      <h1 class="display-5 fw-bold lh-1 mb-3 text-white text-center text-lg-start">سبل البريد السعودي</h1>
                      <p class="lead text-white text-center text-lg-start">فعالية عن اليوم العالمي للصحة النفسية</p>
                    </div>
                    <div class="col-12 col-lg-7">
                      <div class="w-80 mx-auto rounded-4 bg-light" style="height: 200px;"></div>
                    </div>
                  </div>
                </div>

              </div>
            </div>

            <div class="carousel-item">
              <div class="w-75 mx-auto rounded-4" style="min-height: 300px; background: linear-gradient(45deg, #2424FF, #1B0C75);">

                <div class="container p-5">
                  <div class="row flex-lg-row align-items-center g-2 g-lg-5 py-1">
                    <div class="col-12 col-lg-5">
                      <h1 class="display-5 fw-bold lh-1 mb-3 text-white text-center text-lg-start">سبل البريد السعودي</h1>
                      <p class="lead text-white text-center text-lg-start">فعالية عن اليوم العالمي للصحة النفسية</p>
                    </div>
                    <div class="col-12 col-lg-7">
                      <div class="w-80 mx-auto rounded-4 bg-light" style="height: 200px;"></div>
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

    <!-- testimonial section -->
    <section class="position-relative">
      <div class="position-absolute bg-image w-50 h-75 bottom-0 start-0" style="background-image: url('assets/images/bg_testimonial.png'); background-size: contain; background-repeat: no-repeat;"></div>
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold">آراء عملائنا</h2>
            </div>
          </div>
        </div>

        <div class="container overflow-hidden pb-4">
          <div class="row g-4">
            <div class="col-12 col-md-6 col-lg-4 align-self-center">
              <div class="bg-white rounded-4 p-3">
                <img src="../../public/assets/images/symbol.png" />
                <p class="my-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet, consectetur</p>
                <h5 class="fw-bold text-primary-thin lh-1 mb-3">Katie Simpson</h5>
              </div>
            </div>
            <div class="col-12 col-md-6 col-lg-4 align-self-center">
              <div class="bg-white rounded-4 p-3">
                <img src="../../public/assets/images/symbol.png" />
                <p class="my-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet, consectetur</p>
                <h5 class="fw-bold text-primary-thin lh-1 mb-3">Marie Ulfa</h5>
              </div>
            </div>
            <div class="col-12 col-md-6 col-lg-4 align-self-center">
              <div class="bg-white rounded-4 p-3">
                <img src="../../public/assets/images/symbol.png" />
                <p class="my-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet, consectetur</p>
                <h5 class="fw-bold text-primary-thin lh-1 mb-3">Richard Blok</h5>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>

    <!-- form section -->
    <section id="partnershipform" class="my-100">
      <div class="container bg-image px-4 position-relative d-flex align-items-center rounded-4"
        style="background-image: url('assets/images/bg_form.png'); background-size: cover; background-position: bottom;">
        <div class="container px-0 px-lg-5 py-3">
          <div class="row flex-lg-row align-items-center g-1 g-md-3 g-lg-5 py-1">
            <div class="col-12 col-md-6">
              <h1 class="display-5 fw-bold lh-2 text-white text-center text-md-start">نتطلع للعمل سوياً لتحقيق شراكة مثمرة!</h1>
            </div>
            <div class="col-12 col-md-6">
              <div class="w-80 mx-auto rounded-1 bg-white p-4">
                <div class="mb-3 mx-2">
                  <input type="text" class="form-control rounded-pill" placeholder="الاسم">
                </div>
                <div class="mb-3 mx-2">
                  <input type="email" class="form-control rounded-pill" placeholder="الايميل">
                </div>
                <div class="mb-3 mx-2">
                  <input type="text" class="form-control rounded-pill" placeholder="رقم الجوال">
                </div>
                <div class="mb-3 mx-2">
                  <input type="text" class="form-control rounded-pill" placeholder="اسم الشركة">
                </div>
                <div class="d-grid mx-2">
                  <button class="btn btn-primary rounded-pill bg-secondary-normal border-0" data-bs-toggle="modal" data-bs-target="#exampleModal">ارسال</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- footer section -->
    <section class="py-4">
      <div class="container">
        <hr>
        <div class="row flex-sm-row-reverse g-3">
          <div class="col-12 col-sm-6 col-md-4">
            <p class="mx-1 fw-bold text-primary-thick">حمل التطبيق</p>
            <div class="d-flex flex-wrap">
              <a href="javascript:void(0);"><img src="../../public/assets/images/download_appgallery.png" class="mx-1"/></a>
              <a href="javascript:void(0);"><img src="../../public/assets/images/download_appstore.png" class="mx-1"/></a>
              <a href="javascript:void(0);"><img src="../../public/assets/images/download_googleplay.png" class="mx-1"/></a>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-2">
            <span class="mx-1 fw-bold text-primary-thick">تواصل معنا</span>
            <p class="mx-1 my-2 text-primary-thick">920026612 / 0580033345</p>
          </div>
          <div class="col-12 col-sm-6 col-md-3">
            <p class="mx-1 fw-bold text-primary-thick">تابعنا</p>
            <div class="d-flex flex-wrap">
              <div class="border border-1 rounded-circle mx-1">
                <a href="javascript:void(0);"><img src="../../public/assets/images/contact_facebook.png" /></a>
              </div>
              <div class="border border-1 rounded-circle mx-1">
                <a href="javascript:void(0);"><img src="../../public/assets/images/contact_instagram.png" /></a>
              </div>
              <div class="border border-1 rounded-circle mx-1">
                <a href="javascript:void(0);"><img src="../../public/assets/images/contact_linkedin.png" /></a>
              </div>
              <div class="border border-1 rounded-circle mx-1">
                <a href="javascript:void(0);"><img src="../../public/assets/images/contact_twitter.png" /></a>
              </div>
              <div class="border border-1 rounded-circle mx-1">
                <a href="javascript:void(0);"><img src="../../public/assets/images/contact_web.png" /></a>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-3">
            <a href="#"><img src="../../public/assets/images/logo_dark.png"/></a>
          </div>
        </div>
      </div>
    </section>
</div>
</template>

<style scoped>
.hero {
  height: auto;
}
.hero-title {
  text-align: center;
  font-size: 25px;
}
.hero-title-margin {
  margin-left: 0%;
  margin-right: 0%;
  margin-top: 10px;
  margin-bottom: 10px;
}
.hero-image {
  position: relative;
  width: 50%;
  left: 0;
  margin: 0 auto;
}
.feature-card {
  width: 100%;
}
.feature-bg {
  height: 100% !important;
}
/* Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) {
  .hero {
    height: auto;
  }
  .hero-title {
    text-align: center;
    font-size: 40px;
  }
  .hero-title-margin {
    text-align: center;
    margin-left: 0%;
    margin-right: 0%;
    margin-top: 10px;
    margin-bottom: 10px;
  }
  .hero-image {
    position: relative;
    width: 50%;
    left: 0;
    margin: 0 auto;
  }
  .feature-card {
    width: 100%;
  }
  .feature-bg {
    height: 100% !important;
  }
}
/* Medium devices (tablets, 768px and up) */
@media (min-width: 768px) {
  .hero {
    height: 600px;
  }
  .hero-title {
    text-align: start;
    font-size: 45px;
  }
  .hero-title-margin {
    margin-left: 2%;
    margin-right: 2%;
    margin-top: 140px;
    margin-bottom: 140px;
  }
  .hero-image {
    position: absolute;
    width: 550px;
    left: 0%;
  }
  .feature-card {
    width: 75%;
  }
  .feature-bg {
    height: auto !important;
  }
}
/* Large devices (desktops, 992px and up) */
@media (min-width: 992px) {
  .hero {
    height: 100vh;
  }
  .hero-title {
    text-align: start;
    font-size: 45px;
  }
  .hero-title-margin {
    margin-left: 5%;
    margin-right: 5%;
    margin-top: 140px;
    margin-bottom: 140px;
  }
  .hero-image {
    position: absolute;
    width: 65%;
    left: 4%;
  }
  .feature-card {
    width: 50%;
  }
}
/* X-Large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) {
  .hero {
    height: 100vh;
  }
  .hero-title {
    text-align: start;
    font-size: 60px;
  }
  .hero-title-margin {
    margin-left: 8%;
    margin-right: 8%;
    margin-top: 100px;
    margin-bottom: 100px;
  }
  .hero-image {
    position: absolute;
    width: 50%;
    left: 8%;
  }
}
.my-100 {
  margin-top: 100px;
  margin-bottom: 100px;
}
.border-primary-thick {
  border-color: #1B0C75 !important;
}
.text-primary-thin {
  color: #2424FF;
}
.text-primary-normal {
  color: #1F17AF;
}
.text-primary-thick {
  color: #1B0C75;
}
.bg-primary-thin {
  background-color: #2424FF;
}
.bg-primary-normal {
  background-color: #1F17AF;
}
.bg-primary-thick {
  background-color: #1B0C75;
}
.bg-secondary-normal {
  background-color: #EA6838;
}
.slider {
  position: relative;
  width: 100%;

  display: grid;
  place-items: center;
  overflow: hidden;
}
.slider::before,
.slider::after{
  position: absolute;
  background-image: linear-gradient(to right,rgba(255,255,255,1) 0%,rgba(255,255,255,0) 100%);
  content: '';
  height: 100%; width: 25%;
  z-index: 2; pointer-events: none;
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
  width: calc(180px * 16);
  height: 200px;
  display: flex;
  animation: scroll 20s linear infinite;
  justify-content: space-between;
}
.slide-track2 {
  width: calc(180px * 18);
  height: 200px;
  display: flex;
  animation: scroll2 20s linear infinite;
  justify-content: space-between;
}

.slide-item {
  width: 180px;
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
    transform: translateX(calc(-180px * 8));
  }
}
@keyframes scroll2 {
  0% {
    transform: translateX(0px);
  }
  100% {
    transform: translateX(calc(-180px * 9));
  }
}

@media screen and (max-width: 768px) {
  .slide-track {
    width: calc(150px * 16);
  }
  .slide-track2 {
    width: calc(150px * 18);
  }
  .slide-item {
    width: 150px;
  }
  @keyframes scroll {
    0% {
      transform: translateX(0px);
    }
    100% {
      transform: translateX(calc(-150px * 8));
    }
  }
  @keyframes scroll2 {
    0% {
      transform: translateX(0px);
    }
    100% {
      transform: translateX(calc(-150px * 9));
    }
  }
}

.carousel-indicators [data-bs-target] {
  width: 20px; height: 20px;
  background-color: gray;
}
.carousel-indicators .active {
  background-color: #EA6838;
}
</style>
