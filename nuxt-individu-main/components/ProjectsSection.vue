<template>
  <section class="projects">
    <div class="container">
      <h2 class="section-title">My Projects</h2>
      <div class="project-list">
        <div class="project-item">
          <h3>Project 1</h3>
          <p>Ini adalah project pribadi saya membuat Ecommerce dengan menggunakan React Tailwind.</p>
          <a href="https://github.com/Whyawww/Ecommerce-React-Tailwind" class="btn">View Project</a>
        </div>
        <div class="project-item">
          <h3>Project 2</h3>
          <p>Ini adalah pembuatan aplikasi pemesanan tiket film bioskop menggunakan bahasa C</p>
          <a href="https://github.com/Whyawww/Cinema-Project" class="btn">View Project</a>
        </div>
        <!-- Tambahkan proyek-proyek lain di sini -->
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
.projects {
  padding: 50px 0;
  background: linear-gradient(135deg, #f6d365, #fda085); /* Gradien warna latar belakang */
  color: #333; /* Warna teks */
  overflow-x: auto; /* Aktifkan scroll horizontal */
  white-space: nowrap; /* Pastikan konten tidak pindah ke baris baru */
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.section-title {
  font-size: 2.5rem;
  text-align: center;
  margin-bottom: 30px;
  color: #fff; /* Warna judul lebih terang untuk kontras */
}

.project-list {
  display: flex;
  justify-content: flex-start; /* Mulai dari kiri */
  flex-wrap: nowrap; /* Pastikan tidak bungkus konten ke baris baru */
}

.project-item {
  background-color: #808836;
  padding: 20px;
  margin-right: 20px; /* Ruang antar proyek */
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  min-width: 300px; /* Lebar minimum proyek */
  text-align: center;
  flex: 0 0 auto; /* Tetapkan ukuran flex item */
}

.btn{
  background: linear-gradient(135deg, #f6d365, #fda085);
}

.project-item:last-child {
  margin-right: 0; /* Hapus margin kanan untuk item terakhir */
}

.project-item h3 {
  font-size: 1.5rem;
  margin-bottom: 10px;
}

.project-item p {
  font-size: 1rem;
  margin-bottom: 15px;
}

.project-item .btn {
  display: inline-block;
  padding: 8px 16px;
  background-color: #4285F4; /* Warna tombol */
  color: #fff;
  text-decoration: none;
  border-radius: 4px;
  transition: background-color 0.3s ease;
}

.project-item .btn:hover {
  background-color: #3367d6; /* Warna tombol saat hover */
}
@media (max-width: 991.98px) {
  .hero .card {
    margin-bottom: 30px;
  }
}
</style>
