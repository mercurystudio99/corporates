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
      <!-- <div class="position-relative">
        <div class="z-2 position-absolute end-0">
          <img src="../assets/images/service.png" width="100%" height="100%"/>
        </div>
      </div> -->
    </div>
  </div>
</template>

<style scoped></style>
