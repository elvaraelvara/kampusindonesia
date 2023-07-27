<template>
  <div class="beranda-container">
    <header class="header">
      <h1>Selamat datang di Kampus Indonesia!</h1>
      <p class="p">Temukan materi belajar untuk persiapan masuk perguruan tinggi.</p>
      <button class="cta-button">Mulai Belajar</button>
    </header>

    <section class="features">
      <div class="feature">
        <i class="fas fa-book"></i>
        <h3>Materi Lengkap</h3>
        <p>Dapatkan akses ke materi pelajaran yang lengkap dan terstruktur.</p>
      </div>
      <div class="feature">
        <i class="fas fa-users"></i>
        <h3>Pengajar Profesional</h3>
        <p>Belajarlah dari pengajar berpengalaman dan ahli dalam bidangnya.</p>
      </div>
      <div class="feature">
        <i class="fas fa-clock"></i>
        <h3>Waktu Fleksibel</h3>
        <p>Belajarlah sesuai jadwalmu dengan akses 24/7.</p>
      </div>
    </section>

    <section class="content">
      <div class="about-us">
        <h2>Tentang Kami</h2>
        <p>
          Kampus Indonesia adalah platform pembelajaran daring yang berfokus
          pada persiapan masuk perguruan tinggi. Kami menyediakan beragam materi
          pelajaran dari berbagai bidang ilmu, membantu kamu meraih impianmu dalam
          mengenyam pendidikan tinggi.
        </p>
      </div>

      <div class="subject-matter">
        <h2>Materi Pelajaran</h2>
        <p>
          Materi pelajaran kami disusun secara terstruktur dan komprehensif,
          memudahkan kamu dalam memahami setiap topik. Dengan akses 24/7, kamu
          dapat belajar sesuai waktu luangmu tanpa batasan.
        </p>
      </div>

      <div class="professional-instructors">
        <h2>Pengajar Profesional</h2>
        <p>
          Tim pengajar kami terdiri dari para ahli dan praktisi di bidang masing-masing.
          Mereka memiliki pengalaman dalam mengajar dan siap membantu kamu
          dalam mencapai prestasi terbaik.
        </p>
      </div>

      <div class="flexible-access">
        <h2>Akses Fleksibel</h2>
        <p>
          Nikmati fleksibilitas belajar dengan menggunakan perangkat apapun,
          dari laptop hingga ponsel pintar. Dengan tampilan responsif, pengalaman
          belajarmu akan tetap optimal di berbagai perangkat.
        </p>
      </div>
    </section>
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
  name: 'Beranda',
};
</script>

<style>
  /* Add your CSS styles here */
  .beranda-container {
    font-family: Arial, sans-serif;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }

  .header {
    text-align: center;
    margin-bottom: 30px;
    background: linear-gradient(to bottom, #003366, #0056b3);
    color: #fff;
    padding: 40px 0;
    border-radius: 4px;
  }

  .p{
    color: #fff;
  }
  h1 {
    font-size: 36px;
    margin-bottom: 10px;
  }

  p {
    font-size: 18px;
    color: #777;
  }

  .cta-button {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 12px 24px;
    font-size: 16px;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
    background: linear-gradient(to bottom, #007bff, #0056b3);
  }

  .cta-button:hover {
    background-color: #0056b3;
  }

  .features {
    display: flex;
    justify-content: space-between;
    margin-bottom: 30px;
  }

  .feature {
    text-align: center;
    flex-basis: 30%;
    padding: 20px;
    background-color: #f9f9f9;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    background-color: #f0f0f0;
  }

  .feature i {
    font-size: 36px;
    margin-bottom: 10px;
    color: #007bff;
  }

  h3 {
    font-size: 24px;
    margin-bottom: 10px;
  }

  .content {
    text-align: center;
  }

  .content h2 {
    font-size: 28px;
    margin-bottom: 20px;
    color: #003366; /* Ubah warna judul h2 */
  }

  .content p {
    font-size: 18px;
    line-height: 1.6;
    color: #444;
    margin-bottom: 30px;
  }

  /* Gaya untuk menambahkan efek hover pada h2 dan p */
  .content h2:hover,
  .content p:hover {
    color: #0056b3; /* Ubah warna teks saat dihover */
    cursor: pointer;
  }

  /* Gaya untuk menambahkan efek ketika h2 diberi tanda garis bawah */
  .content h2 {
    border-bottom: 2px solid #007bff;
    padding-bottom: 5px;
    display: inline-block;
  }

  /* Gaya untuk menampilkan ikon yang sesuai di h2 */
  .content h2::before {
    content: "\f135"; /* Kode ikon FontAwesome (ganti sesuai ikon yang diinginkan) */
    font-family: "Font Awesome 5 Free"; /* Pastikan Anda telah memuat Font Awesome */
    display: inline-block;
    margin-right: 10px;
    font-size: 20px;
    color: #007bff; /* Ubah warna ikon */
  }

  .footer {
    background-color: #003366;
    color: #fff;
    padding: 20px 0;
    text-align: center;
  }

  .footer-content {
    max-width: 800px;
    margin: 0 auto;
  }

  .footer p {
    font-size: 14px;
    margin: 5px 0;
  }

  .footer a {
    color: #fff;
    text-decoration: none;
  }

  .footer a:hover {
    text-decoration: underline;
  }
</style>
