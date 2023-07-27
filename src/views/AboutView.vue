<template>
  <div class="materi-container">
    <h1>Daftar Materi</h1>
    <ul class="materi-list">
      <li class="materi-item">
        <i class="fas fa-calculator"></i>
        <div class="materi-info">
          <h2>Matematika</h2>
          <p>
            Pelajari berbagai konsep matematika seperti aljabar, trigonometri,
            dan kalkulus untuk persiapan masuk perguruan tinggi.
          </p>
        </div>
      </li>
      <li class="materi-item">
        <i class="fas fa-flask"></i>
        <div class="materi-info">
          <h2>Kimia</h2>
          <p>
            Pelajari reaksi kimia, struktur molekul, dan berbagai konsep kimia
            lainnya untuk persiapan ujian masuk perguruan tinggi.
          </p>
        </div>
      </li>
      <li class="materi-item">
        <i class="fas fa-microscope"></i>
        <div class="materi-info">
          <h2>Fisika</h2>
          <p>
            Pelajari hukum-hukum fisika, gerak benda, dan berbagai fenomena
            alam untuk persiapan masuk perguruan tinggi.
          </p>
        </div>
      </li>
      <!-- Tambahkan lebih banyak mata pelajaran di sini -->
    </ul>
    <footer class="footer">
      <div class="footer-content">
        <p>&copy; 2023 Kampus Indonesia. All rights reserved.</p>
        <p>Contact us: info@kampusindonesia.com</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'Materi',
};
</script>

<style>
/* CSS style untuk halaman Materi */

.materi-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
}

h1 {
  font-size: 2.5rem;
  text-align: center;
  margin-bottom: 2rem;
}

h2{
  color: #fdfdfd;
}

.materi-list {
  list-style: none;
  padding: 0;
}

.materi-item {
  display: flex;
  align-items: center;
  margin-bottom: 2rem;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-radius: 5px;
  padding: 1.5rem;
  background: linear-gradient(to bottom, #003366, #0056b3);
}

.materi-item i {
  font-size: 2.5rem;
  margin-right: 1.5rem;
  color: #6c5ce7;
}

.materi-info h2 {
  font-size: 1.8rem;
  margin-bottom: 1rem;
}

.materi-info p {
  font-size: 1.1rem;
  color: #fdfdfd;
}

.materi-item:hover {
  transform: translateY(-5px);
  transition: transform 0.2s ease;
}
</style>
