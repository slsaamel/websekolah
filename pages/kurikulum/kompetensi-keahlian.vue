<template>
  <div class="container-fluid">
    <!-- Header -->
    <div class="row">
      <div class="col-lg-12 p-3"></div>
      <div class="col-lg-12">
        <h4 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
          Kompetensi Keahlian <b>SMKN 4 TASIKMALAYA</b>
        </h4>
      </div>
      <div class="col-lg-12">
        <p style="background-color: whitesmoke;" class="rounded-3 p-1 m-3 text-secondary">
          <NuxtLink to="/" class="text-decoration-none">Kurikulum</NuxtLink> / Kompetensi Keahlian
        </p>
      </div>
    </div>

    <!-- Kartu Kompetensi Keahlian -->
    <div class="row">
      <!-- Kartu 1 -->
      <div class="col-lg-3 col-md-6 mb-4">
        <div class="card shadow-sm text-center" style="width: 100%;">
          <div class="icon-container mx-auto mt-3">
            <img src="/assets/DKV.jpg" class="card-icon" alt="Icon Kompetensi 1">
          </div>
          <div class="card-body">
            <h5 class="card-title text-center">DKV</h5>
            <p class="card-text">
              Penjelasan singkat tentang kompetensi keahlian ini untuk memberikan informasi yang berguna.
            </p>
          </div>
        </div>
      </div>

      <!-- Kartu 2 -->
      <div class="col-lg-3 col-md-6 mb-4">
        <div class="card shadow-sm text-center" style="width: 100%;">
          <div class="icon-container mx-auto mt-3">
            <img src="/assets/PPLG.jpg" class="card-icon" alt="Icon Kompetensi 2">
          </div>
          <div class="card-body">
            <h5 class="card-title text-center">PPLG</h5>
            <p class="card-text">
              Penjelasan singkat tentang kompetensi keahlian ini untuk memberikan informasi yang berguna.
            </p>
          </div>
        </div>
      </div>

      <!-- Kartu 3 -->
      <div class="col-lg-3 col-md-6 mb-4">
        <div class="card shadow-sm text-center" style="width: 100%;">
          <div class="icon-container mx-auto mt-3">
            <img src="/assets/TKJT.jpg" class="card-icon" alt="Icon Kompetensi 3">
          </div>
          <div class="card-body">
            <h5 class="card-title text-center">TJKT</h5>
            <p class="card-text">
              Penjelasan singkat tentang kompetensi keahlian ini untuk memberikan informasi yang berguna.
            </p>
          </div>
        </div>
      </div>

       <!-- Kartu 4 -->
       <div class="col-lg-3 col-md-6 mb-4">
        <div class="card shadow-sm text-center" style="width: 100%;">
          <div class="icon-container mx-auto mt-3">
            <img src="/assets/TOI.JPG" class="card-icon" alt="Icon Kompetensi 3">
          </div>
          <div class="card-body">
            <h5 class="card-title text-center">TOI</h5>
            <p class="card-text">
              Penjelasan singkat tentang kompetensi keahlian ini untuk memberikan informasi yang berguna.
            </p>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Mengatur gaya untuk gambar agar terlihat seperti ikon */
.card-icon {
  width: 80px;
  height: 80px;
  border-radius: 50%; /* Membuat gambar berbentuk lingkaran */
  object-fit: cover;
  border: 2px solid #ddd; /* Menambahkan border untuk estetika */
}

.icon-container {
  width: 100px;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f9f9f9; /* Warna latar belakang untuk ikon */
  border-radius: 50%;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
}

.card {
  border-radius: 10px;
}

.card-body {
  text-align: justify;
}

.shadow-sm {
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
}
</style>
