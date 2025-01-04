<template>
  <div class="news-page">
    <header class="news-header">
      <p>Temukan informasi terbaru tentang kegiatan dan acara di sekolah kami.</p>
    </header>
    <section class="news-list">
      <div v-for="newsItem in news" :key="newsItem.id" class="news-card">
        <img :src="newsItem.image" :alt="newsItem.title" class="news-image" />
        <div class="news-content">
          <h2 class="news-title">{{ newsItem.title }}</h2>
          <p class="news-summary">{{ newsItem.summary }}</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "BeritaPage",
  data() {
    return {
      news: [
        {
          id: 1,
          title: "JUARA LkS RPL",
          summary:
            "Enam Siswa Smkn4 juara LKS RPL.",
          image: "https://radartasik.id/wp-content/uploads/2023/04/LKS-RPL.jpg",
        },
        {
          id: 2,
          title: "Tujuh Siswa Smk raih beasiswa",
          summary:
            "Tujuh siswa smkn4 raih beasiswa dari astra honda motor.",
          image: "https://assets.radartasik.id/main/2024/10/SMKN-4-tasikmalaya-raih-beasiswa-AHM.webp",
        },
        {
          id: 3,
          title: "Peresmian kerja sama ",
          summary:
            "Peresmian kerja sama dengan astra hondra motor.",
          image: "https://asset-2.tstatic.net/jabar/foto/bank/images/Peresmian-antara-PT-Daya-Adicipta-Motora-dan-SMK-Negeri-4-Tasikmalaya.jpg",
          
        },
      ],
    };
  },
};
</script>

<style scoped>
/* Gaya Umum Halaman */
.news-page {
  font-family: 'Arial', sans-serif;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  text-align: center;
}

/* Header */
.news-header {
  margin-bottom: 30px;
}

.news-header h1 {
  font-size: 2.5rem;
  color: #333;
  margin-bottom: 10px;
}

.news-header p {
  font-size: 1.2rem;
  color: #666;
}

/* Daftar Berita */
.news-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

/* Kartu Berita */
.news-card {
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.news-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

/* Gambar Berita */
.news-image {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

/* Konten Berita */
.news-content {
  padding: 15px;
}

.news-title {
  font-size: 1.5rem;
  color: #333;
  margin-bottom: 10px;
}

.news-summary {
  font-size: 1rem;
  color: #555;
  margin-bottom: 15px;
}

/* Tautan "Baca Selengkapnya" */
.read-more {
  text-decoration: none;
  color: #007bff;
  font-size: 1rem;
}

.read-more:hover {
  text-decoration: underline;
}
</style>