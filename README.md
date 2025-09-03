<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dashboard Profil - Andry Irawan</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="dashboard">
    <aside class="sidebar">
      <div class="profile">
        <img src="images/profile.jpg" alt="Foto Profil" class="profile-img">
        <h2>Andry Irawan</h2>
        <p class="role">Web Developer</p>
      </div>
      <nav>
        <ul>
          <li><a href="#tentang"><span>🏠</span> Beranda</a></li>
          <li><a href="#portofolio"><span>💼</span> Portofolio</a></li>
          <li><a href="#kontak"><span>✉️</span> Kontak</a></li>
        </ul>
      </nav>
      <div class="sosmed">
        <a href="https://instagram.com/andryirawan7" target="_blank" title="Instagram">
          <!-- Instagram SVG -->
          <svg width="26" height="26" viewBox="0 0 24 24" fill="#E1306C"><path d="M12 2.2c3.2 0..."/></svg>
        </a>
        <a href="https://github.com/andryirawan7-dot" target="_blank" title="GitHub">
          <!-- GitHub SVG -->
          <svg width="26" height="26" viewBox="0 0 24 24" fill="#181717"><path d="M12 .3a12 12 0..."/></svg>
        </a>
        <a href="mailto:andryirawan7@gmail.com" title="Email">
          <!-- Email SVG -->
          <svg width="26" height="26" viewBox="0 0 24 24" fill="#EA4335"><path d="M12 13.065c-.279..."/></svg>
        </a>
      </div>
    </aside>
    <main class="main-content">
      <header>
        <h1>Selamat Datang di Dashboard Saya!</h1>
      </header>
      <section id="tentang">
        <h2>Tentang Saya</h2>
        <p>Saya adalah seorang developer yang suka membuat web sederhana dan ingin terus belajar teknologi baru.</p>
      </section>
      <section id="portofolio">
        <h2>Portofolio</h2>
        <div class="card-list">
          <div class="card">
            <h3>Website Company Profile</h3>
            <p>Membuat website profil perusahaan dengan tampilan modern dan responsive.</p>
          </div>
          <div class="card">
            <h3>Aplikasi To-Do List</h3>
            <p>Aplikasi pencatat tugas harian dengan fitur drag and drop.</p>
          </div>
          <!-- Tambahkan kartu portofolio lain sesuai kebutuhan -->
        </div>
      </section>
      <section id="kontak">
        <h2>Kontak</h2>
        <p>Email: <a href="mailto:andryirawan7@gmail.com">andryirawan7@gmail.com</a></p>
        <p>Instagram: <a href="https://instagram.com/andryirawan7" target="_blank">@andryirawan7</a></p>
      </section>
    </main>
  </div>
</body>
</html>
