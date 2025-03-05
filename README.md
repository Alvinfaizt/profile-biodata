# profile-biodata
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Biodata</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        .container { width: 80%; margin: auto; }
        .menu { background: #333; padding: 10px; text-align: center; }
        .menu a { color: white; margin: 0 15px; text-decoration: none; }
        .section { padding: 50px 0; }
        .flex { display: flex; justify-content: space-between; align-items: center; }
        .bio-box { width: 30%; background: #f4f4f4; padding: 20px; margin: 10px; text-align: center; }
        .portfolio img { width: 100%; max-width: 300px; margin: 10px; }
    </style>
</head>
<body>
    <!-- Section 1: Menu -->
    <div class="menu">
        <a href="#biodata">Biodata</a>
        <a href="#portfolio">Portofolio</a>
    </div>

    <!-- Section 2: Judul di Kiri, Gambar di Kanan -->
    <div class="container section flex" id="biodata">
        <div>
            <h1>Profil Saya</h1>
            <p>Selamat datang di halaman profil saya.</p>
        </div>
        <div>
            <img src="profile.jpg" alt="Foto Profil" width="300">
        </div>
    </div>

    <!-- Section 3: Biodata dengan 6 Box -->
    <div class="container section flex" style="flex-wrap: wrap;">
        <div class="bio-box">Nama: John Doe</div>
        <div class="bio-box">Usia: 25 Tahun</div>
        <div class="bio-box">Pekerjaan: Web Developer</div>
        <div class="bio-box">Email: john@example.com</div>
        <div class="bio-box">Alamat: Jakarta, Indonesia</div>
        <div class="bio-box">Hobi: Coding & Desain</div>
    </div>

    <!-- Section 4: Portofolio -->
    <div class="container section portfolio" id="portfolio">
        <h2>Portofolio</h2>
        <div class="flex" style="flex-wrap: wrap;">
            <img src="portfolio1.jpg" alt="Project 1">
            <img src="portfolio2.jpg" alt="Project 2">
            <img src="portfolio3.jpg" alt="Project 3">
        </div>
    </div>
</body>
</html>
