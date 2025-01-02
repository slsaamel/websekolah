<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
          <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
            Statstik Data SMKN 4 Tasikmalaya
          </h5>
        </div>
        <div class="col-lg-12">
          <p style="background-color: whitesmoke;" class="rounded-3 p-1 m-3 text-secondary">
            <NuxtLink to="/propil" class="text-decoration-none">Profil</NuxtLink>/ DataStatistik
          </p>
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
</template>

<style scoped>
.statistik-data {
  font-family: Arial, sans-serif;
  margin: 20px;
}

.breadcrumb {
  font-size: 14px;
  color: gray;
  margin-bottom: 20px;
}

.content {
  background-color: #f9f9f9;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

h1 {
  text-align: center;
  margin-bottom: 20px;
}

h2 {
  text-align: center;
  margin-bottom: 20px;
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