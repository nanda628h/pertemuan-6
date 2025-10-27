## Nama : ananda Friezy Eka Cahya
## NIM: 312410151

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About - Web Framework</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <a class="navbar-brand fw-bold" href="index.html">My Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link active" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <section class="bg-light text-center py-5">
    <div class="container">
      <h1 class="display-5 fw-bold">Tentang Kami</h1>
      <p class="lead text-muted">Halaman ini menjelaskan profil dan tujuan pembuatan website Bootstrap pada praktikum ini.</p>
    </div>
  </section>

  <!-- CONTENT -->
  <div class="container my-5">
    <div class="row">
      <div class="col-md-8">
        <h2>Profil Website</h2>
        <p>Website ini dibuat sebagai bagian dari tugas Praktikum 6 - Web Framework, Program Studi Teknik Informatika Universitas Pelita Bangsa. Tujuannya adalah mempelajari penggunaan framework CSS, khususnya Bootstrap, untuk membuat layout web yang responsif.</p>
        <p>Dengan Bootstrap, pembuatan halaman web menjadi lebih mudah dan cepat karena sudah disediakan banyak komponen seperti navbar, card, grid, dan tombol.</p>
      </div>
      <div class="col-md-4">
        <img src="https://dummyimage.com/350x250/6c757d/fff.png" class="img-fluid rounded" alt="About Image">
      </div>
    </div>
  </div>

  <!-- FEATURETTE -->
  <div class="container my-5">
    <hr class="featurette-divider">
    <div class="row featurette align-items-center">
      <div class="col-md-7">
        <h2 class="featurette-heading fw-normal lh-1">Mengapa Bootstrap?</h2>
        <p class="lead">Bootstrap merupakan framework yang paling populer di dunia karena mudah digunakan dan mendukung desain responsif untuk semua ukuran layar.</p>
      </div>
      <div class="col-md-5">
        <img src="https://dummyimage.com/150x150/9b9b9b/fff.png" class="img-fluid rounded" alt="Featurette">
      </div>
    </div>
  </div>

  <!-- FOOTER -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 - Universitas Pelita Bangsa</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```



<img width="1524" height="844" alt="image" src="https://github.com/user-attachments/assets/500b761d-a38e-4011-a7a2-a78955aaa8a8" />


```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Web Framework</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <a class="navbar-brand fw-bold" href="index.html">My Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link active" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <section class="bg-light text-center py-5">
    <div class="container">
      <h1 class="display-5 fw-bold">Hubungi Kami</h1>
      <p class="lead text-muted">Anda dapat menghubungi kami melalui form berikut atau informasi kontak yang tersedia.</p>
    </div>
  </section>

  <!-- FORM KONTAK -->
  <div class="container my-5">
    <div class="row">
      <div class="col-md-6">
        <h2>Formulir Kontak</h2>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Nama</label>
            <input type="text" class="form-control" id="name" placeholder="Masukkan nama Anda">
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email</label>
            <input type="email" class="form-control" id="email" placeholder="Masukkan email Anda">
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Pesan</label>
            <textarea class="form-control" id="message" rows="4" placeholder="Tulis pesan Anda di sini..."></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Kirim</button>
        </form>
      </div>

      <div class="col-md-6">
        <h2>Informasi Kontak</h2>
        <p><strong>Alamat:</strong> Jl. Insinyur H. Juanda, Cikarang, Bekasi</p>
        <p><strong>Email:</strong> info@pelitabangsa.ac.id</p>
        <p><strong>Telepon:</strong> (021) 2121212121</p>
        <div class="mt-3">
        </div>
      </div>
    </div>
  </div>

  <!-- FOOTER -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 - Universitas Pelita Bangsa</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```



<img width="1542" height="860" alt="image" src="https://github.com/user-attachments/assets/b8ee5140-6ac8-4cee-acbf-a1f48d2bd0e7" />


```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Web Framework</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <a class="navbar-brand fw-bold" href="index.html">My Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link active" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <section class="bg-light text-center py-5">
    <div class="container">
      <h1 class="display-5 fw-bold">Hubungi Kami</h1>
      <p class="lead text-muted">Anda dapat menghubungi kami melalui form berikut atau informasi kontak yang tersedia.</p>
    </div>
  </section>

  <!-- FORM KONTAK -->
  <div class="container my-5">
    <div class="row">
      <div class="col-md-6">
        <h2>Formulir Kontak</h2>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Nama</label>
            <input type="text" class="form-control" id="name" placeholder="Masukkan nama Anda">
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email</label>
            <input type="email" class="form-control" id="email" placeholder="Masukkan email Anda">
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Pesan</label>
            <textarea class="form-control" id="message" rows="4" placeholder="Tulis pesan Anda di sini..."></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Kirim</button>
        </form>
      </div>

      <div class="col-md-6">
        <h2>Informasi Kontak</h2>
        <p><strong>Alamat:</strong> Jl. Insinyur H. Juanda, Cikarang, Bekasi</p>
        <p><strong>Email:</strong> info@pelitabangsa.ac.id</p>
        <p><strong>Telepon:</strong> (021) 2121212121</p>
        <div class="mt-3">
        </div>
      </div>
    </div>
  </div>

  <!-- FOOTER -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 - Universitas Pelita Bangsa</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

