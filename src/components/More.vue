<template>
  <div class="py-5" id="more">
    <div class="container my-5 d-none d-md-block">
      <!-- Desktop -->
      <div class="row ">
        <div class="col">
          <img src="images/team.png" class="img-fluid" />
        </div>
        <div class="col">
          <h5>Kenal lebih dekat dengan developer VITRI</h5>
          <button type="button" class="btn btn-outline-warning boksbtn">
            Tentang Kami <b-icon-arrow-right-square />
          </button>
        </div>
      </div>
     
      
    </div> 
    <!-- Mobile -->
    <div class="container d-sm-block d-md-none mx-2">
      <div class="row justify-content-center">
        
          <img src="images/team.png" class="img-fluid" />
        
        
          <h5>Kenal lebih dekat dengan developer VITRI</h5>
          <a href="/about">
          <button type="button" class="btn btn-outline-warning boksbtn">
            Tentang Kami <b-icon-arrow-right-square />
          </button>
          </a>
          
        
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "More",
};
</script>

<style>
</style>