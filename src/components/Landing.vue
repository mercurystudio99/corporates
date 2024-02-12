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
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (1).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (2).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (3).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (4).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (5).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (6).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (7).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (8).png" />
            </div>
            <!-- same slides doubled (duplicate) -->
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (1).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (2).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (3).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (4).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (5).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (6).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (7).png" />
            </div>
            <div class="slide">
              <img src="../../public/assets/images/icon_offer (8).png" />
            </div>
          </div>
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

.slide {
  width: 150px;
  display: grid;
  place-items: center;
  transition:0.5s;
  cursor:pointer;
}
.slide:hover{
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
  .slide {
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
</style>
