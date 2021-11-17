<template>
  <div class="hero">
    <video id="background-video" autoplay loop muted poster="images/hero.png">
      <source src="videos/mockbackground.mp4" type="video/mp4" />
    </video>
    <!-- Desktop -->
    <div class="container d-none d-lg-block">
      <div class="col-6">
        <div class="row ml-1">
          <h1>Vision Based</h1>
        </div>
        <div class="row ml-1">
          <h1>Traffic Analytics</h1>
        </div>
        <div class="row ml-1">
          <p>
            Analisis kepadatan lalulintas secara real-time berdasarkan citra
            kamera pengawas lalulintas
          </p>
        </div>
        <div class="row">
          <div class="col">
            <a href="#tentang">
              <button type="button" class="btn btn-warning ml-0 mr-2 boksbtn">
                Dashboard
              </button>
            </a>
            <a href="#tentang">
              <button
                type="button"
                class="btn btn-outline-warning boksbtn-line"
                href="#tentang"
              >
                About <b-icon-arrow-down-square />
              </button>
            </a>
          </div>
        </div>
      </div>
      <div class="col"></div>
    </div>
    <!-- Mobile -->
    <div class="container d-sm-block d-lg-none">
      <div class="row mx-2 align-items-center text-center">
        <div class="h1 ">
          Vision Based Traffic Analytics
        </div>
        <p>
          Analisis kepadatan lalulintas secara real-time berdasarkan citra
            kamera pengawas lalulintas
        </p>
        <div class="col">
          
            <a href="#tentang">
              <button type="button" class="btn btn-warning my-2 boksbtn">
                Dashboard
              </button>
            </a>
            <a href="#tentang">
              <button
                type="button"
                class="btn btn-outline-warning ml-0 boksbtn-line"
                href="#tentang"
              >
                About <b-icon-arrow-down-square />
              </button>
            </a>
          
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>