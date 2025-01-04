<template>
  <div class="ekskul-page">
    <header>
      <h1>Ekstrakurikuler Sekolah</h1>
    </header>
    <section class="ekskul-list">
      <div
        v-for="activity in activities"
        :key="activity.id"
        class="ekskul-item"
      >
        <img :src="activity.logo" :alt="activity.name" class="ekskul-logo" />
        <h2 class="ekskul-name">{{ activity.name }}</h2>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "EkstrakurikulerPage",
  data() {
    return {
      activities: [
        {
          id: 1,
          name: "Basketball",
          logo: "https://static.vecteezy.com/system/resources/previews/014/468/355/original/badminton-jumping-smash-illustration-logo-design-modern-passionate-badminton-player-in-action-logo-design-template-vector.jpg",
        },
        {
          id: 2,
          name: "Paskibra",
          logo: "https://down-id.img.susercontent.com/file/id-11134207-7qul9-lk57huxtby22f5",
        },
        {
          id: 3,
          name: "Pmr",
          logo: "https://th.bing.com/th/id/R.c51795b02f76b3cdcc2f48fcda86add4?rik=S11P52k8NMUEyg&riu=http%3a%2f%2f2.bp.blogspot.com%2f-WA2WLzyzOTQ%2fU3BgtDPbBhI%2fAAAAAAAAAbY%2fDKgWAZQv5aA%2fs1600%2fLOGO%2b-%2bPMI.png&ehk=Ig8Xqo2%2bZlNH9zxvPPxTKKO3YWA389pDepb9Lfz0sQg%3d&risl=&pid=ImgRaw&r=0",
        },
        {
          id: 4,
          name: "Volly",
          logo: "https://image.freepik.com/vector-gratis/logo-voleibol_20448-58.jpg",
        },
        {
          id: 5,
          name: "Basket ball",
          logo: "https://th.bing.com/th/id/OIP.jZrQQnH97EYkctbabhEXCgAAAA?rs=1&pid=ImgDetMain",
        },
        {
          id: 6,
          name: "Sepak bola",
          logo: "https://png.pngtree.com/png-clipart/20230705/original/pngtree-football-logo-vector-png-image_9260276.png"
        },
        {
          id: 7,
          name: "Perisai diri",
          logo: "https://1.bp.blogspot.com/-GugSeZpGMsc/YMtYPVFXWuI/AAAAAAAAIl0/R_DT6UXTm3IrefHdR6M0w5FBp0-gWd6VgCLcBGAsYHQ/w1200-h630-p-k-no-nu/logo-perisai-diri.png"
        },
        {
          id: 8,
          name: "Futsal",
          logo: "https://th.bing.com/th/id/OIP.v_3OSEuxPa2lpmLNfo3ZswHaHa?w=675&h=675&rs=1&pid=ImgDetMain"
        },
        {
          id: 9,
          name: "Pks",
          logo: "https://4.bp.blogspot.com/_jmKom7WjjgA/TOE3WkpC_JI/AAAAAAAAAB8/eWkFWXbY4Ec/s1600/PKS+LOGO.jpg"
        },
        {
          id: 10,
          name: "English club",
          logo: "https://th.bing.com/th/id/R.34fed92c7149101b8d7cb743e2a75d3c?rik=1AFgT2x3iCZ13A&riu=http%3a%2f%2fwww.spcs.edu.hk%2fcurriculum%2fclubs%2fEnglish%2feng_club.jpg&ehk=OxA5cDucWYKmjKyD%2fj8am7p1uDu0MfiNqC516q%2fyUpY%3d&risl=&pid=ImgRaw&r=0"
        }

      ],
    };
  },
};
</script>

<style scoped>
.ekskul-page {
  font-family: Arial, sans-serif;
  text-align: center;
  margin: 20px auto;
  max-width: 1200px;
}

header h1 {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #333;
}

.ekskul-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  padding: 10px;
}

.ekskul-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  background: #f9f9f9;
  border-radius: 10px;
  padding: 15px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s;
}

.ekskul-item:hover {
  transform: scale(1.05);
}

.ekskul-logo {
  width: 80px;
  height: 80px;
  object-fit: contain;
  margin-bottom: 10px;
}

.ekskul-name {
  font-size: 1.2rem;
  color: #555;
}
</style>