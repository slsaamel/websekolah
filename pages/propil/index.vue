<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
          <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
            Profil <b>SMKN 4 TASIKMALAYA</b>
          </h5>
        </div>
        <div class="col-lg-12">
          <p style="background-color: whitesmoke;" class="rounded-3 p-1 m-3 text-secondary">
            <NuxtLink to="/profil" class="text-decoration-none">Profil</NuxtLink>
          </p>
        </div>
        <div class="row mt-3">
        <!-- Teknik Komputer dan Jaringan -->
        <div class="col-lg-12 mb-3">
          <div class="card">
            <div class="card-header bg-light">
              <h5 class="text-center"> Sejarah SMK Negeri 4 Tasikmalaya</h5>
            </div>
            <div class="card-body">
              <p>
                Sejalan dengan Program Pemerintah dibidang pendidikan Menengah Kejuruan pada saat itu yakni 
                pemerataan akses ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan adanya
                SMK Negeri di daerah Kecamatan Purbaratu Kota  Tasikmalaya, terutama untuk menampung tamatan
                dari SLTP yang ingin melanjutkan ke SMK maka beberapa tokoh masyarakat, unsur pejabat pemerintah
                di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada pemerintah Kota Tasikmalaya dan
                Pemerintah Provinsi Jawa Barat, agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.
              </p>
              <!-- Tombol Aksi -->
              <div class="text-center">
                <NuxtLink to="/propil/sejarah">
                  <button class="btn btn-primary me-2">Read More</button>
                </NuxtLink>
                  
              </div>
            </div>
          </div>
        </div>
        
        <div class="col-lg-12 mb-3">
          <div class="card">
            <div class="card-header bg-light">
              <h5 class="text-center"> Visi dan Misi SMK Negeri 4 Tasikmalaya</h5>
            </div>
            <div class="card-body">
              <h5 class="col-3">Visi:</h5><p>Dengan Berlandaskan Iman dan Taqwa Menghasilkan Tamatan yang Cerdas,Akhlak mulia, Kreatif, Aktif, Produktif (CAKAP)</p>
              <h5>Misi:</h5><p>1.Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.<br>
                2.Meningkatkan dan mengembangkan aktifitas serta kreatifitas seluruh warga sekolah dalam berbagai kegiatan positif.<br>
                3.Mewujudkan manajemen pengelolaan yang efektif, efesien, transparan, akuntabel dan layanan prima</p>
              <!-- Tombol Aksi -->
              <div class="text-center">
               <NuxtLink to="/propil/visi-misi">
                  <button class="btn btn-primary me-2">Read More</button>
                </NuxtLink>
              </div>
            </div>
          </div>
        </div>
  
        <div class="col-lg-12 mb-3">
          <div class="card">
            <div class="card-header bg-light">
              <h5 class="text-center"> Identitas Sekolah Menengah Kejuruan Negeri 4 Tasikmalaya</h5>
            </div>
            <div class="card-body">
              <table class="n4table tableidentitas">
            <tbody>
              <tr>
                <td>
                  <b>a.</b>
                </td>
                <td>
                  <b>Nama Sekolah</b>
                </td>
                <td>:</td>
                <td>SMK Negeri 4 Kota Tasikmalaya</td>
              </tr>
              <tr>
                <td>
                  <b>b.</b>
                </td>
                <td>
                  <b>NPSN</b>
                </td>
                <td>:</td>
                <td>20276063</td>
              </tr>
              <tr>
                <td>
                  <b>c.</b>
                </td>
                <td>
                  <b>Nomor Statistik Sekolah</b>
                </td>
                <td>:</td>
                <td>401327810004</td>
              </tr>
              <tr>
                <td>
                  <b>d.</b>
                </td>
                <td>
                  <b>Alamat</b>
                </td>
                <td>:</td>
                <td></td>
              </tr>
              <tr>
                <td></td>
                <td>Jalan</td>
                <td>:</td>
                <td>Jl Depok RT 02 RW 05</td>
              </tr>
              <tr>
                <td></td>
                <td>Kelurahan</td>
                <td>:</td>
                <td>Sukamenak</td>
              </tr>
              <tr>
                <td></td>
                <td>Kecamatan</td>
                <td>:</td>
                <td>Purbaratu</td>
              </tr>
              <tr>
                <td></td>
                <td>Kota</td>
                <td>:</td>
                <td>Tasikmalaya</td>
              </tr>
            </tbody>
          </table>
              <!-- Tombol Aksi -->
              <div class="text-center">
                  <button class="btn btn-primary me-2">Read More</button>
              </div>
            </div>
          </div>
        </div>
  
        </div>
    </div>
  </div>
  </template>