<template>
  <section class="about">
    <div class="container">
      <h2 class="section-title">About Me</h2>
      <div class="content">
        <p>Saya adalah frontend</p>
        <p>Setiap harinya saya sering membuat sebuah website seperti Ecommerce dan lain lain.</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>

<style scoped>
.about {
  padding: 50px 0;
  background: linear-gradient(135deg, #f6d365, #fda085);
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
  color: #333; /* Warna judul lebih gelap */
}

.content {
  text-align: justify;
  line-height: 1.6;
  color: #666; /* Warna teks */
}

@media (max-width: 768px) {
  .section-title {
    font-size: 2rem;
  }
}
</style>
