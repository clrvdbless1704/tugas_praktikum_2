<h1>Laporan Praktikum 2</h1>

<h3>Project: Membuat Website Curriculum Vitae menggunakan HTML dan CSS</h3>
<h3>Nama  : Gabriel Jehuda Tamedo</h3>
<h3>NIM   : 42430007</h3>
<hr>
<h3>Deskripsi Proyek</h3>
<p>Project ini berupa website Curriculum Vitae (CV) online milik Gabriel Jehuda Tamedo. Website ini dibuat menggunakan HTML untuk struktur konten dan CSS untuk styling agar tampilan lebih menarik, rapi, dan profesional.</p>
<p><b>Website ini terdiri dari:</b></p>
<ul>
  <li><b>Home Page</b> – halaman sambutan dan link menuju CV.</li>
  <li><b>Curriculum Vitae Page</b> – halaman utama yang menampilkan biodata, pendidikan, skill, dan kontak.</li>
</ul>
<hr>
<h3>Fitur Utama Website</h3>
<ol>
  <li><b>Home page</b></li>
    <ul>
      <li>Menampilkan perkenalan singkat.</li>
      <li>Link ke halaman Curriculum Vitae</li>
    </ul>
  <li><b>Halaman CV</b></li>
    <ul>
      <li><b>Navigasi Cepat</b>(Biodata, Pendidikan, Skill, Kontak)</li>
      <li><b>Foto profil</b> dengan styling CSS (lingkaran)</li>
      <li><b>Bagian Biodata</b> yang memuat identitas singkat.</li>
      <li><b>Bagian Pendidikan</b> dengan list sekolah & tahun.</li>
      <li><b>Bagian Skill</b> dengan level kemampuan.</li>
      <li><b>Bagian Kontak</b> berupa nomor, email, serta link ke media sosial (Facebook, Instagram, GitHub).</li>
    </ul>
</ol>
<hr>
<h3>Struktur Proyek</h3>
<p><b>Dokumen HTML:</b></p>
  <ul>
    <li><b>home-page.html</b> - Halaman utama (welcome page).</li>
    <li><b>curriculum_vitae_gabriel.html</b> - Halaman Curriculum Vitae.</li>
  </ul>
<p><b>Dokumen CSS:</b></p>
  <ul>
    <li><b>style.css</b> - File CSS untuk styling halaman.</li>
  </ul>
<p><b>Dokumen Gambar:</b></p>
  <ul>
    <li><b>Gabriel Profile.jpeg</b> - Foto profil.</li>
  </ul>
<hr>
<h3>Penjelasan Baris Kode</h3>
<h4>Struktur HTML</h4>
<ul>
  <li>!DOCTYPE html</li>
    <p>!DOCTYPE html = Mendeklarasikan bahwa dokumen menggunakan HTML5.</p>
  <li>html lang="en" /html</li>
    <p>html lang="en" = Elemen pembungkus utama dengan atribut bahasa. </p>
  <li>head /head</li>
    <p>head = Elemen yang menjadi wadah informasi penting.</p>
      <ul>
        <li>meta charset="UTF-8" =  supaya teks bisa terbaca semua karakter.</li>
        <li>meta name="viewport" =  biar responsif di semua ukuran layar.</li>
        <li>title /title = judul halaman di tab browser.</li>
        <li>link rel="stylesheet" href="style.css" =  menghubungkan HTML dengan CSS.</li>
      </ul>
<br>
  <li>body /body</li>
    <p>body = Semua konten utama website (navigasi, foto, biodata, skill, kontak) ada di sini.</p>
  <li>nav /nav</li>
    <p>nav = Memakai anchor a buat pindah langsung ke section Biodata, Pendidikan, Skill, Kontak.</p>
  <li>img src="Gabriel Profile.jpeg</li>
    <p>img = Menampilkan foto Gabriel dengan class cv-img (diatur di CSS jadi lingkaran).</p>
  <li>section id="Biodata" /section</li>
    <p>section = Menjelaskan identitas singkat (tempat/tanggal lahir, status, dan studi).</p>
  <li>ul li /li /ul</li>
    <p>ul li = Ditampilkan dalam bentuk list dengan nama sekolah & tahun.</p>
  <li>section id="Skill" /section</li>
    <p>section = List kemampuan dengan level (Intermediate, Beginner, Elementary).</p>
  <li>section id="Kontak" /section</li>
    <p>section = Menyimpan informasi kontak (telp, email, media sosial, GitHub).
</ul>
  
<h4>Struktur CSS</h4>
<ul>
  <li>body = atur font utama, kasih background biru tua, serta hilangkan margin & padding default.</li>
  <li>.cv-container = bikin box putih transparan dengan shadow dan rounded corner biar lebih modern.</li>
  <li>.cv-header = pakai flexbox supaya foto dan teks sejajar horizontal.</li>
  <li.cv-img = foto profil dibuat lingkaran dengan border-radius: 85%, diberi border abu-abu.</li>
  <li>.cv-info = atur warna, ukuran font, dan jarak antar elemen biodata.</li>
  <li>.cv-details h2 = setiap judul section (Biodata, Pendidikan, dll) dikasih border top + margin biar rapi.</li>
  <li>.cv-details ul & li = ilangkan bullet list default, atur warna font & spacing antar item.</li>
  <li>.home-container = sama kayak cv-container, tapi khusus untuk halaman home (welcome page).</li>
</ul>
<hr>
<h3>Kesimpulan</h3>
<p>Website CV ini berhasil dibangun dengan memanfaatkan kombinasi HTML (struktur konten) dan CSS (styling tampilan). Elemen semantik seperti section, nav, ul sudah dipakai dengan baik untuk bikin struktur lebih rapi dan mudah dipahami. CSS memberikan sentuhan modern, seperti penggunaan flexbox, shadow, border radius, dan background, sehingga website terlihat bagus dan gampang diakses.</p>





















  
