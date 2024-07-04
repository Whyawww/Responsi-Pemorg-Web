<template>
  <section class="contact">
    <div class="container">
      <h2 class="section-title">Contact Me</h2>
      <div class="content">
        <p>Email: wajinusantara05@gmail.com</p>
        <p>Phone: 082116219128</p>
        <p>Social Media:</p>
        <ul>
          <li><a href="https://instagram.com/jiwhyn" target="_blank" rel="noopener">Instagram</a></li>
          <li><a href="https://www.linkedin.com/in/WahyuAji/" target="_blank" rel="noopener">LinkedIn</a></li>
          <li><a href="https://github.com/Whyawww" target="_blank" rel="noopener">GitHub</a></li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
.contact {
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
  text-align: center;
  color: #666; /* Warna teks */
}

ul {
  list-style-type: none;
  padding: 0;
  margin-top: 20px;
  text-align: center;
}

ul li {
  display: inline-block;
  margin: 0 10px;
}

ul li a {
  color: #4285F4; /* Warna link */
  text-decoration: none;
}

ul li a:hover {
  text-decoration: underline;
}
@media (max-width: 991.98px) {
  .hero .card {
    margin-bottom: 30px;
  }
}
</style>
