<template>
  <div id="app">
    <div class="container">
      <!-- Slider Berita -->
      <div class="slider">
        <div class="slider-content">
          <img src="/assets/guru.jpg" alt="Berita" class="slider-image" />
        </div>
       </div>

      <!-- Sambutan Kepala Sekolah -->
      <div class="sambutan">
        <h3>Sambutan Kepala Sekolah</h3>
        <div class="sambutan-content">
          <img src="/assets/kep.jpg" alt="Kepala Sekolah" class="kepsek-image" />
          <marquee direction="up" scrollamount="2" class="marquee-text">
            Assalamu'alaikum Wr, Wb<br /><br />
            Puji Syukur kepada Allah SWT, Tuhan yang maha esa yang telah memberikan rahmat dan anugerahnya sehingga WEBSITE SMKN 4 TASIKMALAYA ini dapat terbit. salah satu tujuan dari website ini adalah
            untuk menjawab akan setiap kebutuhan informasi dengan memanfaatkan sarana teknologi informasi yang ada. 
          </marquee>
        </div>
      </div>
    </div>
  </div>

  <div class="container-fluid">
    <!-- Header -->
    <div class="row">
      <div class="col-lg-12 p-3">
      </div>
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
       <!-- Kartu Kompetensi Keahlian -->
    <div class="row d-flex justify-content-center">
      <!-- Kartu 1 -->
      <div class="col-lg-4 col-md-6 mb-4">
        <div class="card shadow-sm text-center" style="width: 100%;">
          <div class="icon-container mx-auto mt-3">
            <img src="/assets/DKV.jpg" class="card-icon" alt="Icon Kompetensi 1" style="width: 20%;">
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
      <div class="col-lg-4 col-md-6 mb-4">
        <div class="card shadow-sm text-center" style="width: 100%;">
          <div class="icon-container mx-auto mt-3">
            <img src="/assets/PPLG.jpg" class="card-icon" alt="Icon Kompetensi 2" style="width: 20%;">
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
      <div class="col-lg-4 col-md-6 mb-4">
        <div class="card shadow-sm text-center" style="width: 100%;">
          <div class="icon-container mx-auto mt-3">
            <img src="/assets/TKJ.jpg" class="card-icon" alt="Icon Kompetensi 3" style="width: 20%;">
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
       <div class="col-lg-4 col-md-6 mb-4">
        <div class="card shadow-sm text-center" style="width: 100%;">
          <div class="icon-container mx-auto mt-3">
            <img src="/assets/TOI.jpg" class="card-icon" alt="Icon Kompetensi 3" style="width: 20%;">
          </div>
          <div class="card-body">
            <h5 class="card-title text-center">TOI</h5>
            <p class="card-text">
              Penjelasan singkat tentang kompetensi keahlian ini untuk memberikan informasi yang berguna.
            </p>
          </div>
        </div>
      </div>

      <!-- Kartu 5 -->
      <div class="col-lg-4 col-md-6 mb-4">
        <div class="card shadow-sm text-center" style="width: 100%;">
          <div class="icon-container mx-auto mt-3">
            <img src="/assets/TBSM.jpg" class="card-icon" alt="Icon Kompetensi 3" style="width: 20%;">
          </div>
          <div class="card-body">
            <h5 class="card-title text-center">TBSM</h5>
            <p class="card-text">
              Penjelasan singkat tentang kompetensi keahlian ini untuk memberikan informasi yang berguna.
            </p>
          </div>
        </div>
      </div>

       <!-- Pendidik dan Tenaga Kependidikan -->
       <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5 class="text-center"> Pendidik dan Tenaga Kependidikan</h5>
          </div>
          <div class="card-body">
            <div class="row">
              <!-- Jumlah Guru PNS -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-primary text-white">
                    <h6 class="text-center mb-0">Jumlah Guru PNS</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 7 orang</p>
                    <p>Perempuan: 3 orang</p>
                    <p>Total: 10 orang</p>
                  </div>
                </div>
              </div>
              <!-- Jumlah Guru Honorer -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-secondary text-white">
                    <h6 class="text-center mb-0">Jumlah Guru Honorer</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 20 orang</p>
                    <p>Perempuan: 10 orang</p>
                    <p>Total: 30 orang</p>
                  </div>
                </div>
              </div>
              <!-- Jumlah Tenaga Administrasi PNS -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-success text-white">
                    <h6 class="text-center mb-0">Jumlah Tenaga Administrasi PNS</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 2 orang</p>
                    <p>Perempuan: 1 orang</p>
                    <p>Total: 3 orang</p>
                  </div>
                </div>
              </div>
              <!-- Jumlah Tenaga Administrasi Honorer -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-warning text-white">
                    <h6 class="text-center mb-0">Jumlah Tenaga Administrasi Honorer</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 3 orang</p>
                    <p>Perempuan: 2 orang</p>
                    <p>Total: 5 orang</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
        <div class="content">
      <h2>Statistik Data</h2>
      <div class="stats-grid">
        <div class="stat-item">
          <h3>Jumlah Siswa</h3>
          <p class="value">1116</p>
        </div>
        <div class="stat-item">
          <h3>Jumlah Rombel</h3>
          <p class="value">34</p>
        </div>
        <div class="stat-item">
          <h3>Jumlah Guru</h3>
          <p class="value">60</p>
        </div>
        <div class="stat-item">
          <h3>Jumlah Tenaga Administrasi</h3>
          <p class="value">10</p>
        </div>
      </div>
      </div>

      
    </div>
    </div>
    </div>

</template>

<script>
export default {
  name: "App",
};
</script>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
}

.container {
  display: flex;
  gap: 20px;
  padding: 20px;
}

/* Slider */
.slider {
  flex: 3;
  position: relative;
  background-color: #fff;
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  overflow: hidden;
}

.slider-content {
  padding: 20px;
  text-align: center;
}

.slider-content h2 {
  font-size: 18px;
  background-color: rgba(0, 0, 0, 0.7);
  color: #fff;
  padding: 10px;
  border-radius: 5px;
}

.slider-content p {
  margin: 10px 0;
  font-size: 14px;
  color: #555;
}

.slider-image {
  width: 100%;
  height: auto;
  margin: 10px 0;
}

.slider-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.btn-berita {
  background-color: #007bff;
  color: #fff;
  padding: 8px 15px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.btn-berita:hover {
  background-color: #0056b3;
}

.tanggal {
  font-size: 12px;
  color: #888;
}

.slider-btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: rgba(0, 0, 0, 0.5);
  color: #fff;
  border: none;
  border-radius: 50%;
  padding: 10px;
  cursor: pointer;
  font-size: 16px;
}

.slider-btn-left {
  left: 10px;
}

.slider-btn-right {
  right: 10px;
}

/* Sambutan Kepala Sekolah */
.sambutan {
  flex: 1;
  background-color: #fff;
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  overflow: hidden;
  text-align: center;
}

.sambutan h3 {
  background-color: #007bff;
  color: #fff;
  padding: 10px;
  margin: 0;
}

.sambutan-content {
  padding: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.kepsek-image {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-bottom: 10px;
}

.marquee-text {
  width: 100%;
  font-size: 14px;
  color: #555;
}
.card-header {
  font-weight: bold;
  font-size: 1.1rem;
}
.card-body p {
  margin-bottom: 10px;
  text-align: justify;
} 

.stats-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
}

.stat-item {
  background-color: #bfebfe;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.stat-item h3 {
  margin-bottom: 10px;
}

.stat-item .value {
  font-size: 24px;
  font-weight: bold;
}
</style>