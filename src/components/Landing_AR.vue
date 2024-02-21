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
          <div class="d-flex justify-content-between align-items-center py-4">
            <a href="#"><img src="../../public/assets/images/logo.png" width="100"/></a>
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
              <h2 class="almarai-font-extrabold hero-title fw-bold lh-1 mb-3 text-white lh-sm">برنامج مكافآت <br /> الموظفين والعملاء</h2>
              <div class="d-grid gap-2 d-flex justify-content-center justify-content-md-start my-4">
                <a href="#partnershipform" class="btn btn-primary btn-hero px-4 me-md-2 rounded-pill bg-secondary-normal border-0"><span class="almarai-font-regular">عرض تجريبي</span></a>
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
    <section class="mt-50">
      <div class="position-relative">
        <h2 class="my-4 display-5 text-center text-primary-thick fw-bold almarai-font-bold">أبرز العلامات التجارية</h2>
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
    <section class="mt-50 position-relative" style="margin-top: 20px;">
      <div class="position-absolute bg-image w-50 feature-bg bottom-0 start-0" style="background-image: url('assets/images/bg_program.png'); background-size: contain; background-repeat: no-repeat;"></div>
      <div class="position-relative">

        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold almarai-font-bold">خدمات برنامج الشركات</h2>
            </div>
          </div>
        </div>

        <div class="container overflow-hidden">
          <div class="row gx-4 gy-2 m-4">
            <div class="col-12 col-md-6 pr-lg-15">
              <div class="rounded-end rounded-5 p-2 bg-gray">
                <div class="d-flex justify-content-between align-items-center">
                  <span class="mx-2 text-primary-thick fw-normal almarai-font-regular">عروض لجميع موظفي الشركة وأفراد أسرهم</span>
                  <img src="../../public/assets/images/icon_infinite.png" width="50" height="50" />
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6 pr-lg-15">
              <div class="rounded-end rounded-5 p-2 bg-gray">
                <div class="d-flex justify-content-between align-items-center">
                  <span class="mx-2 text-primary-thick fw-normal almarai-font-regular">شراء وتوصيل الهدايا للموظفين</span>
                  <img src="../../public/assets/images/icon_gift.png" width="50" height="50" />
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6 pr-lg-15">
              <div class="rounded-end rounded-5 p-2 bg-gray">
                <div class="d-flex justify-content-between align-items-center">
                  <span class="mx-2 text-primary-thick fw-normal almarai-font-regular">شحن رصيد الموظف لشراء هدايا</span>
                  <img src="../../public/assets/images/icon_wallet.png" width="50" height="50" />
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6 pr-lg-15">
              <div class="rounded-end rounded-5 p-2 bg-gray">
                <div class="d-flex justify-content-between align-items-center">
                  <span class="mx-2 text-primary-thick fw-normal almarai-font-regular">خدمة عملاء لضمان رضا  الموظفين</span>
                  <img src="../../public/assets/images/icon_tool.png" width="50" height="50" />
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6 pr-lg-15">
              <div class="rounded-end rounded-5 p-2 bg-gray">
                <div class="d-flex justify-content-between align-items-center">
                  <span class="mx-2 text-primary-thick fw-normal almarai-font-regular">تنظيم الفعاليات الداخلية الخاصة بالشركة</span>
                  <img src="../../public/assets/images/icon_congrat.png" width="50" height="50" />
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6 pr-lg-15">
              <div class="rounded-end rounded-5 p-2 bg-gray">
                <div class="d-flex justify-content-between align-items-center">
                  <span class="mx-2 text-primary-thick fw-normal almarai-font-regular">إضافة عروض  بناء على طلب الشركة</span>
                  <img src="../../public/assets/images/icon_upload.png" width="50" height="50" />
                </div>
              </div>
            </div>

          </div>
        </div>

      </div>
    </section>

    <!-- mobile app section -->
    <section class="mt-50 screenshot-main">
      <div class="container">
        <div class="row justify-content-md-center">
          <div class="col-12">
            <h2 class="my-4 display-5 text-center text-primary-thick fw-bold almarai-font-bold">تطبيق يعكس هوية شركتك</h2>
          </div>
        </div>
      </div>

      <div class="d-flex overflow-hidden justify-content-center px-1 px-lg-4 my-4">
        <div class="mx-1 mx-lg-4">
          <img src="../../public/assets/images/phone1.png" width="100%" style="min-width: 100px;"/>
        </div>
        <div class="mx-1 mx-lg-4">
          <img src="../../public/assets/images/phone2.png" width="100%" style="min-width: 100px;"/>
        </div>
        <div class="mx-1 mx-lg-4">
          <img src="../../public/assets/images/phone3.png" width="100%" style="min-width: 100px;"/>
        </div>
        <div class="mx-1 mx-lg-4">
          <img src="../../public/assets/images/phone4.png" width="100%" style="min-width: 100px;"/>
        </div>
        <div class="mx-1 mx-lg-4">
          <img src="../../public/assets/images/phone5.png" width="100%" style="min-width: 100px;"/>
        </div>
      </div>
    </section>

    <!-- mobile app section in Mobile version -->
    <section class="mt-50 screenshot-mobile">
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold almarai-font-bold">تطبيق يعكس هوية شركتك</h2>
            </div>
          </div>
        </div>

        <div id="carouselMobileIndicators" class="carousel slide" data-bs-ride="carousel" data-bs-touch="true">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <div class="w-50 mx-auto">
                <img src="../../public/assets/images/phone1.png" width="100%"/>
              </div>
            </div>
            <div class="carousel-item">
              <div class="w-50 mx-auto">
                <img src="../../public/assets/images/phone2.png" width="100%"/>
              </div>
            </div>
            <div class="carousel-item">
              <div class="w-50 mx-auto">
                <img src="../../public/assets/images/phone3.png" width="100%"/>
              </div>
            </div>
            <div class="carousel-item">
              <div class="w-50 mx-auto">
                <img src="../../public/assets/images/phone4.png" width="100%"/>
              </div>
            </div>
            <div class="carousel-item">
              <div class="w-50 mx-auto">
                <img src="../../public/assets/images/phone5.png" width="100%"/>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- companies section -->
    <section class="mt-50">
      <div class="position-relative">
        <h2 class="my-4 display-5 text-center text-primary-thick fw-bold almarai-font-bold">شركاء يقدمون مزايا SDC App لموظفيهم</h2>
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
    <section class="mt-50 position-relative">
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold almarai-font-bold">مزايا التطبيق</h2>
            </div>
          </div>
        </div>

        <div class="feature-item" style="margin-top: 15px;">
          <div class="container">
            <div class="row">
              <div class="col-4">
                <div class="mx-auto feature-card">
                  <div class="bg-primary-thick rounded-4 p-3 p-sm-4 mx-2 mx-sm-4">
                      <img src="../../public/assets/images/icon_infinite_light.png" width="100%" height="100%" />
                  </div>
                </div>
                <p class="text-center my-4 feature-caption">Unlimited Discounts and offers</p>
              </div>
              <div class="col-4">
                <div class="mx-auto feature-card">
                  <div class="bg-primary-thick rounded-4 p-3 p-sm-4 mx-2 mx-sm-4">
                      <img src="../../public/assets/images/icon_wallet_light.png" width="100%" height="100%" />
                  </div>
                </div>
                <p class="text-center my-4 feature-caption">Discounts, Guaranteed</p>
              </div>
              <div class="col-4">
                <div class="mx-auto feature-card">
                  <div class="bg-primary-normal rounded-4 p-3 p-sm-4 mx-2 mx-sm-4">
                      <img src="../../public/assets/images/icon_star_light.png" width="100%" height="100%" />
                  </div>
                </div>
                <p class="text-center my-4 feature-caption">Points on every transaction</p>
              </div>
            </div>
          </div>
        </div>

        <div class="feature-item">
          <div class="container">
            <div class="row justify-content-center">
              <div class="col-4">
                <div class="mx-auto feature-card">
                  <div class="bg-primary-thin rounded-4 p-3 p-sm-4 mx-2 mx-sm-4">
                      <img src="../../public/assets/images/icon_clock_light.png" width="100%" height="100%" />
                  </div>
                </div>
                <p class="text-center my-4 feature-caption">Track your savings</p>
              </div>
              <div class="col-4">
                <div class="mx-auto feature-card">
                  <div class="bg-primary-normal rounded-4 p-3 p-sm-4 mx-2 mx-sm-4">
                      <img src="../../public/assets/images/icon_phone_light.png" width="100%" height="100%" />
                  </div>
                </div>
                <p class="text-center my-4 feature-caption">Brands information</p>
              </div>
            </div>
          </div>
        </div>

      </div>
    </section>

    <!-- event section -->
    <section class="mt-50">
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold almarai-font-bold">فعاليات سابقة</h2>
            </div>
          </div>
        </div>

        <div id="carouselEventIndicators" style="padding-bottom: 0.75rem;" class="carousel slide" data-bs-ride="carousel" data-bs-touch="true">
          <div class="carousel-indicators">
            <div data-bs-target="#carouselEventIndicators" data-bs-slide-to="0" class="active rounded-circle" aria-current="true" aria-label="Slide 1"></div>
            <div data-bs-target="#carouselEventIndicators" data-bs-slide-to="1" class="rounded-circle" aria-label="Slide 2"></div>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <div class="w-75 mx-auto rounded-4" style="background: linear-gradient(45deg, #2424FF, #1B0C75);">

                <div class="container px-5 pt-2 pb-5 p-lg-5">
                  <div class="row flex-lg-row align-items-center g-2 g-lg-5 py-1">
                    <div class="col-12 col-lg-5">
                      <h1 class="display-5 fw-bold almarai-font-bold lh-1 mb-3 text-white text-center text-lg-end">سبل البريد السعودي</h1>
                      <p class="lead text-white text-center text-lg-end almarai-font-regular">فعالية عن اليوم العالمي للصحة النفسية</p>
                    </div>
                    <div class="col-12 col-lg-7">
                      <div class="w-80 mx-auto rounded-4 bg-light">
                        <div class="ratio ratio-16x9">
                          <iframe src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0" title="YouTube video"></iframe>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

              </div>
            </div>

            <div class="carousel-item">
              <div class="w-75 mx-auto rounded-4" style="background: linear-gradient(45deg, #2424FF, #1B0C75);">

                <div class="container px-5 pt-2 pb-5 p-lg-5">
                  <div class="row flex-lg-row align-items-center g-2 g-lg-5 py-1">
                    <div class="col-12 col-lg-5">
                      <h1 class="display-5 fw-bold almarai-font-bold lh-1 mb-3 text-white text-center text-lg-end">سبل البريد السعودي</h1>
                      <p class="lead text-white text-center text-lg-end almarai-font-regular">فعالية عن اليوم العالمي للصحة النفسية</p>
                    </div>
                    <div class="col-12 col-lg-7">
                      <div class="w-80 mx-auto rounded-4 bg-light">
                        <div class="ratio ratio-16x9">
                          <iframe src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0" title="YouTube video"></iframe>
                        </div>
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

    <!-- testimonial section -->
    <section class="mt-50 position-relative screenshot-main">
      <div class="position-absolute bg-image w-25 feature-bg bottom-0 start-0" style="background-image: url('assets/images/bg_testimonial.png'); background-size: contain; background-repeat: no-repeat;"></div>
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold almarai-font-bold">آراء عملائنا</h2>
            </div>
          </div>
        </div>

        <div class="container overflow-hidden pb-4">
          <div class="row g-4">
            <div class="col-12 col-md-6 col-lg-4 align-self-center">
              <div class="shadow bg-white rounded-4 p-3">
                <img src="../../public/assets/images/symbol.png" />
                <p class="my-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet, consectetur</p>
                <h5 class="fw-bold text-primary-thin lh-1 mb-3">Katie Simpson</h5>
              </div>
            </div>
            <div class="col-12 col-md-6 col-lg-4 align-self-center">
              <div class="shadow bg-white rounded-4 p-3">
                <img src="../../public/assets/images/symbol.png" />
                <p class="my-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet, consectetur</p>
                <h5 class="fw-bold text-primary-thin lh-1 mb-3">Marie Ulfa</h5>
              </div>
            </div>
            <div class="col-12 col-md-6 col-lg-4 align-self-center">
              <div class="shadow bg-white rounded-4 p-3">
                <img src="../../public/assets/images/symbol.png" />
                <p class="my-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet, consectetur</p>
                <h5 class="fw-bold text-primary-thin lh-1 mb-3">Richard Blok</h5>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>

    <!-- testimonial section in Mobile version -->
    <section class="mt-50 screenshot-mobile">
      <div class="position-relative">
        <div class="container">
          <div class="row justify-content-md-center">
            <div class="col-12 col-md-10 col-lg-8 col-xl-7 col-xxl-6">
              <h2 class="my-4 display-5 text-center text-primary-thick fw-bold almarai-font-bold">آراء عملائنا</h2>
            </div>
          </div>
        </div>

        <div id="carouselTestimonialIndicators" class="carousel slide" data-bs-ride="carousel" data-bs-touch="true">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <div class="w-75 mx-auto py-4">
                <div class="shadow bg-white rounded-4 p-3">
                  <img src="../../public/assets/images/symbol.png" />
                  <p class="my-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet, consectetur</p>
                  <h5 class="fw-bold text-primary-thin lh-1 mb-3">Katie Simpson</h5>
                </div>
              </div>
            </div>
            <div class="carousel-item">
              <div class="w-75 mx-auto py-4">
                <div class="shadow bg-white rounded-4 p-3">
                  <img src="../../public/assets/images/symbol.png" />
                  <p class="my-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet, consectetur</p>
                  <h5 class="fw-bold text-primary-thin lh-1 mb-3">Marie Ulfa</h5>
                </div>
              </div>
            </div>
            <div class="carousel-item">
              <div class="w-75 mx-auto py-4">
                <div class="shadow bg-white rounded-4 p-3">
                  <img src="../../public/assets/images/symbol.png" />
                  <p class="my-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. Lorem ipsum dolor sit amet, consectetur</p>
                  <h5 class="fw-bold text-primary-thin lh-1 mb-3">Richard Blok</h5>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- form section -->
    <section id="partnershipform" class="mt-100">
      <div class="container bg-image px-4 position-relative d-flex align-items-center rounded-4"
        style="background-image: url('assets/images/bg_form.png'); background-size: cover; background-position: bottom;">
        <div class="container px-0 px-lg-5 py-3">
          <div class="row flex-lg-row align-items-center g-1 g-md-3 g-lg-5 py-1">
            <div class="col-12 col-md-6">
              <h1 class="display-5 fw-bold lh-2 text-white text-center text-md-start almarai-font-bold">نتطلع للعمل سوياً لتحقيق شراكة مثمرة!</h1>
            </div>
            <div class="col-12 col-md-6">
              <div class="w-80 mx-auto rounded-1 bg-white p-4">
                <div class="mb-3 mx-2">
                  <input type="text" class="form-control almarai-font-regular rounded-pill" placeholder="الاسم">
                </div>
                <div class="mb-3 mx-2">
                  <input type="email" class="form-control almarai-font-regular rounded-pill" placeholder="الايميل">
                </div>
                <div class="mb-3 mx-2">
                  <input type="text" class="form-control almarai-font-regular rounded-pill" placeholder="رقم الجوال">
                </div>
                <div class="mb-3 mx-2">
                  <input type="text" class="form-control almarai-font-regular rounded-pill" placeholder="اسم الشركة">
                </div>
                <div class="d-grid mx-2">
                  <button class="btn btn-primary rounded-pill bg-secondary-normal border-0" data-bs-toggle="modal" data-bs-target="#exampleModal"><span class="almarai-font-regular">ارسال</span></button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- footer section -->
    <section class="mt-100 mb-4">
      <div class="mx-4">
        <hr>
        <div class="row flex-sm-row-reverse g-3">
          <div class="col-12 col-sm-6 col-md-4">
            <p class="mx-1 fw-bold almarai-font-bold text-primary-thick">حمل التطبيق</p>
            <div class="d-flex flex-wrap">
              <a href="javascript:void(0);"><img src="../../public/assets/images/download_appgallery.png" class="mx-1"/></a>
              <a href="javascript:void(0);"><img src="../../public/assets/images/download_appstore.png" class="mx-1"/></a>
              <a href="javascript:void(0);"><img src="../../public/assets/images/download_googleplay.png" class="mx-1"/></a>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-3">
            <span class="mx-1 fw-bold almarai-font-bold text-primary-thick">تواصل معنا</span>
            <p class="mx-1 my-3 text-primary-thick">920026612 / 0580033345</p>
          </div>
          <div class="col-12 col-sm-6 col-md-3">
            <p class="mx-1 fw-bold almarai-font-bold text-primary-thick">تابعنا</p>
            <div class="d-flex flex-wrap my-1">
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
          <div class="col-12 col-sm-6 col-md-2">
            <a href="#"><img src="../../public/assets/images/logo_dark.png" width="100"/></a>
          </div>
        </div>
      </div>
    </section>
</div>
</template>

<style scoped>
.almarai-font-bold {
    font-family: "Almarai Bold";
}
.almarai-font-extrabold {
    font-family: "Almarai ExtraBold";
}
.almarai-font-regular {
    font-family: "Almarai Regular";
}
.btn-hero {
  padding: 0.25rem 0.5rem;
  font-size: 1rem;
}
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
.screenshot-main {
  display: none;
}
.screenshot-mobile {
  display: block;
}
.feature-card {
  width: 75%;
}
.feature-item {
  height: 200px;
}
.feature-caption {
  font-size: 1rem;
  font-weight: 500;
}
.feature-bg {
  height: 0 !important;
}
.event-card {
  height: 200px;
}
/* Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) {
  .btn-hero {
    padding: 0.5rem 1rem;
    font-size: 1.25rem;
  }
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
  .screenshot-main {
    display: none;
  }
  .screenshot-mobile {
    display: block;
  }
  .feature-card {
    width: 100%;
  }
  .feature-item {
    height: 260px;
  }
  .feature-caption {
    font-size: 1.25rem;
    font-weight: 500;
  }
  .feature-bg {
    height: 0 !important;
  }
  .event-card {
    height: 200px;
  }
}
/* Medium devices (tablets, 768px and up) */
@media (min-width: 768px) {
  .btn-hero {
    padding: 0.5rem 1rem;
    font-size: 1.25rem;
  }
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
  .screenshot-main {
    display: block;
  }
  .screenshot-mobile {
    display: none;
  }

  .feature-card {
    width: 75%;
  }
  .feature-item {
    height: 260px;
  }
  .feature-caption {
    font-size: 1.25rem;
    font-weight: 500;
  }
  .feature-bg {
    height: 100% !important;
  }
  .event-card {
    height: 200px;
  }
}
/* Large devices (desktops, 992px and up) */
@media (min-width: 992px) {
  .btn-hero {
    padding: 0.5rem 1rem;
    font-size: 1.25rem;
  }
  .hero {
    height: 600px;
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
  .feature-item {
    height: 260px;
  }
  .feature-caption {
    font-size: 1.25rem;
    font-weight: 500;
    margin: 0 auto;
    width: 70%;
  }
  .feature-bg {
    height: 100% !important;
  }
  .event-card {
    height: 200px;
  }
  .carousel-indicators {
    justify-content: start;
  }
}
/* X-Large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) {
  .btn-hero {
    padding: 0.75rem 1.25rem;
    font-size: 1.5rem;
  }
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
  .pr-lg-15 {
    padding-right: 15% !important;
  }
}
.mt-50 {
  margin-top: 50px;
}
.mt-100 {
  margin-top: 100px;
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
.bg-gray {
  background-color: #F5F8FB;
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
  direction: ltr;
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
  width: 15px; height: 15px;
  background-color: rgba(255,255,255,0.4);
}
.carousel-indicators .active {
  background-color: white;
}
.form-control::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
  color: #D1D1D1;
  opacity: 1; /* Firefox */
}
.active.carousel-item-start, .carousel-item-prev:not(.carousel-item-end) {
  transform: translateX(100%);
}
.active.carousel-item-end, .carousel-item-next:not(.carousel-item-start) {
  transform: translateX(-100%);
}
</style>
