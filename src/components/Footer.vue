<template>
  <div class="py-4" id="Footer">
    <div class="container">
      <div class="row">
        <div class="col">
          <div class="row">
            <ul class="footer-links">
              <li class="nav-item">
                <router-link class="nav-link" to="/">Beranda</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/">Tentang</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/">Cara Kerja</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/about">Developer</router-link>
              </li>
            </ul>
            
          </div>
          <div class="row ml-4 logo">
            <img src="images/logo-vitri.svg" width="150">
          </div>
        </div>
        <div class="col info-prak">
            <p>Proyek Mandiri Lintas Disiplin Ilmu I</p>
            <p>Departemen Teknik Elektro dan Informatika</p>
            <p>Sekolah Vokasi</p>
            <p>Universitas Gadjah Mada</p>
            <p>2021</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style></style>
