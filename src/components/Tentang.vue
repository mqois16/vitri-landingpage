<template>
  <div id="tentang">
    <div class="container pt-5">
      <div class="row">
        <div class="col-7">
          <div class="row mb-5">
            <h1>Tentang VITRI</h1>
            <h1 class="underscore">_</h1>
          </div>
          <div class="row mt-3">
            <p>
              Vision Based Traffic Analytics (VITRI) adalah sistem analisis
              lalulintas secara real-time yang mendapatkan data secara langsung
              melalui deteksi moda transportasi dari citra kamera pengawas
              lalilintas yang tersebar.
            </p>
            <p>
              Tujuan dari VITRI adalah untuk mendapatkan dari lalulintas dari
              kamera pengawas lalu diolah menjadi informasi yang readable
              sehingga dapat dijadikan sebagai referensi penentu kebijakan.
            </p>
          </div>
          <div class="row py-3">
            <button type="button" class="btn btn-outline-warning boksbtn">
              Dashboard <b-icon-arrow-right-square />
            </button>
          </div>
        </div>
        <div class="col">
          <img src="images/mobil.gif" class="img-fluid my-5" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Tentang",
};
</script>

<style>
</style>