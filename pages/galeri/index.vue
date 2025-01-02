<template>
  <div class="gallery-container">
    <h1>Galeri Sekolah</h1>
    <div class="row">
      <!-- Kegiatan 1 -->
      <div class="col-md-2 col-sm-6 mb-4">
        <div class="card shadow-lg">
          <img src="assets/nongkrong.jpg" alt="Kegiatan 1" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 2 -->
      <div class="col-md-2 col-sm-6 mb-4">
        <div class="card shadow-lg">
          <img src="/assets/miror.jpg" alt="Kegiatan 2" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 3 -->
      <div class="col-md-2 col-sm-6 mb-4">
        <div class="card shadow-lg">
          <img src="assets/gaya bebas.jpg" alt="Kegiatan 3" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 4 -->
      <div class="col-md-2 col-sm-6 mb-4">
        <div class="card shadow-lg">
          <img src="assets/bergaya.jpg" alt="Kegiatan 4" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 5 -->
      <div class="col-md-2 col-sm-6 mb-4">
        <div class="card shadow-lg">
          <img src="assets/yb.jpg" alt="Kegiatan 5" class="card-img-top" />
        </div>
      </div>

      <!-- Kegiatan 6 -->
      <div class="col-md-2 col-sm-6 mb-4">
        <div class="card shadow-lg">
          <img src="assets/TKJ.jpg" alt="Kegiatan 6" class="card-img-top" />
        </div>
      </div>
    
      </div>
      <div class="col-md-2 col-sm-6 mb-4">
        <div class="card shadow-lg">
          <img src="assets/TBSM.jpg" alt="Kegiatan 6" class="card-img-top" />
        </div>
      </div>

    </div>
  <!-- Footer Section -->
  <footer class="bg-dark text-white text-center py-4">
      <p>&copy; 2024 SMKN 4 Tasikmalaya | Semua Hak Cipta Dilindungi</p>
    </footer>
</template>

<style scoped>
.gallery-container {
  padding: 30px;
  text-align: center;
  background-color: #f8f9fa;
}

h1 {
  margin-bottom: 40px;
  font-size: 2.5rem;
  font-weight: bold;
  color: #343a40;
}

.card-img-top {
  height: 250px;
  object-fit: cover;
  width: 100%;
  border-bottom: 2px solid #ddd;
  border-radius: 8px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card-img-top:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
}

.card-body {
  padding: 15px;
}

.card {
  display: flex;
  flex-direction: column;
  height: 100%;
  border-radius: 8px;
  overflow: hidden;
}

.card-text {
  font-size: 1rem;
  color: #555;
}

p {
  text-align: center;
}

@media (max-width: 768px) {
  .col-md-2 {
    margin-bottom: 20px;
  }
}
</style>