<template>
  <div>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
      <div class="container-fluid">
        <a class="navbar-brand d-flex align-items-center" href="#">
          <img src="/assets/img.jpeg"alt="Logo" width="50" class="me-3" />
          <span class="fw-bold">SMK Negeri 4 Tasikmalaya</span>
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="/">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="berita">Berita</a>
            </li>


            <!-- Dropdown Profil -->
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="/propil"id="navbarDropdownEkskul" role="button"
                data-bs-toggle="dropdown" aria-expanded="false">Profile</a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdownProfil" id="navbarDropdownProfil">
                <li>
                  <nuxt-link to="/propil/sejarah" class="dropdown-item">
                    Sejarah
                  </nuxt-link>
                </li>
                <li>
                  <nuxt-link to="/propil/Visi-Misi" class="dropdown-item">
                    Visi & Misi
                  </nuxt-link>
                </li>
                <li>
                  <nuxt-link to="/propil/Data-Statistik/" class="dropdown-item">
                    Data Statistik
                  </nuxt-link>
                </li>
              </ul>
            </li>
            <!-- Dropdown kurikulum -->
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="kurikulum" id="navbarDropdownEkskul" role="button"
                data-bs-toggle="dropdown" aria-expanded="false">
                Kurikulum
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdownEkskul" id="navbarDropdownEkskul">
                <li><a class="dropdown-item" href="kurikulum/Kompetensi-Keahlian">Kompetensi Keahlian</a></li>
                <!-- Tambahkan ekstrakurikuler lainnya sesuai kebutuhan -->
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="Ekstrakurikuler">Ekstrakurikuler</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="Galeri">Galeri</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
marquee {
  font-size: 14px;
}

.navbar-brand img {
  border-radius: 50%;
}

.nav-link {
  transition: color 0.3s ease;
}

.nav-link:hover {
  color: #4caf50;
}

/* Navbar Styles */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #ffffff;
  box-shadow: 1 5px 10px rgba(0, 0, 0, 0.1);
  padding: 5px 5px;
}

.navbar .logo {
  font-size: 20px;
  font-weight: bold;
}

.navbar ul {
  list-style: none;
  gap: 20px;
  margin: 0;
  padding: 0;
}

.navbar ul li {
  position: relative;
}

.navbar ul li a {
  text-decoration: none;
  color: #333;
  padding: 2px 10px;
  display: block;
  font-size: 13px;
}

/* Dropdown Menu */
.dropdown-menu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background-color: #ffffff;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  z-index: 100;
  min-width: 200px;
}

.dropdown-menu li {
  width: 100%;
}

.dropdown-menu li a {
  padding: 10px;
}

.dropdown:hover .dropdown-menu {
  display: block;
}
</style>