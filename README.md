# Pemrograman-Web
Putri Yanti , Semester lll , Informatika - A
## Here is that is needed
```
fontawesome.com
https://getbootstrap.com/docs/5.0/components/according/
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" 
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
```
## head staxy
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Company Profile</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
      integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
      crossorigin="anonymous"
    />

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
```
## Navigasi 
```
<nav
      class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lg fixed-top"
    >
      <div class="container">
        <a class="navbar-brand" href="#container-fluid benner">Welcome To Planet</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarText"
          aria-controls="navbarText"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse text-right" id="navbarText">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="#layanan">Layanan</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#portofolio">Portofolio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#tentang">Tentang</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#staff">Staff</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#kontak">Kontak Kami</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
```
## Benner
```
<div class="container-fluid banner">
      <div class="container text-center">
        <h4 class="display-6">Selamat Datang di Website Planet</h4>
        <h3 class="display-1">Hai! Halo!</h3>
        <a href="#layanan">
          <button type="button" class="btn btn-danger btn-lg">
            Cek Layanan
          </button>
        </a>
      </div>
    </div>
```
## Layanan
```
<div class="container-fluid layanan pt-5 pb-5">
      <div class="container text-center">
        <h2 class="display-3" id="layanan">Layanan</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate,
          doloribus.
        </p>
        <div class="row pt-4">
          <div class="col-md-4">
            <span class="lingkaran"><i class="fas fa-code fa-5x"></i></span>
            <h3 class="mt-3">Programming</h3>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugiat,
              a!
            </p>
          </div>

          <div class="col-md-4">
            <span class="lingkaran"><i class="fas fa-palette fa-5x"></i></span>
            <h3 class="mt-3">Design</h3>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugiat,
              a!
            </p>
          </div>

          <div class="col-md-4">
            <span class="lingkaran"
              ><i class="fas fa-network-wired fa-5x"></i
            ></span>
            <h3 class="mt-3">Networking</h3>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugiat,
              a!
            </p>
          </div>
        </div>
      </div>
    </div>
```
## Portofolio
```
<div class="container-fluid pt-5 pb-5 bg-light">
      <div class="container text-center">
        <h2 class="display-3" id="portofolio">Portofolio</h2>
        <p>
          PLANET 
        </p>
        <div class="row pt-4 gx-4 gy-4">
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="gambar/M1.webp"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">MERKURIUS.</h5>
                <p class="card-text">
                  Merkurius adalah planet terkecil yang ada di Tata Surya sekaligus yang paling dekat dengan Matahari.                         Periode revolusi dari 
                  planet yang satu ini adalah yang terpendek dari semua planet yang ada di Tata Surya, yaitu 87,79 hari.
                </p>
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="gambar/V1.jfif"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">VENUS.</h5>
                <p class="card-text">
                  Venus merupakan planet inferior dengan sudut elongasi yang mencapai 47,8°.
                Kecerahan maksimal planet ini dapat dilihat segera sebelum matahari terbit atau setelah matahari terbenam, 
                  sehingga disebut Bintang Fajar atau Bintang Senja. Citra Venus yang diproses melalui dua penyaring.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="gambar/B3.jfif"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">BUMI.</h5>
                <p class="card-text">
                  Bumi adalah planet terdekat ketiga dari Matahari yang merupakan planet
                  terpadat dan terbesar kelima dari delapan planet dalam Tata Surya. Bumi juga merupakan
                  planet terbesar dari empat planet kebumian di Tata Surya. Bumi terkadang disebut dengan dunia
                   atau "Planet Biru".
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="gambar/M6.jfif"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">MARS.</h5>
                <p class="card-text">
                  Mars adalah planet terdekat keempat dari Matahari.
                  Namanya diambil dari dewa perang Romawi, Mars. Planet ini sering
                   dijuluki sebagai "planet merah" karena tampak dari jauh berwarna kemerah-kemerahan
                  ni disebabkan oleh keberadaan besi(III) oksida di permukaan planet Mars. 
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="gambar/JS1.jfif"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">JUPITER , SARTUNUS .</h5>
                <p class="card-text">
                  jupiter adalah dunia yang ekstrem. Jupiter adalah planet terbesar di tata surya kita –
                   jika saja Jupiter adalah cangkang berongga, 1.000 Bumi dapat muat di dalamnya.
                   Jupiter juga merupakan planet tertua, 
                  terbentuk dari debu dan gas yang tersisa dari pembentukan Matahari 4,6 miliar tahun yang lalu.
                 
                  Saturnus merupakan planet keenam dari Matahari. Saturnus juga merupakan planet terbesar
                   kedua di Tata Surya setelah Jupiter. 
                  Saturnus juga sebuah raksasa gas yang memiliki radius rata-rata sekitar 9 kali radius rata-rata Bumi.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card crop-img">
              <img
                src="gambar/UN1.jfif"
                class="card-img-top"
                width="200"
                height="200"
              />
              <div class="card-body">
                <h5 class="card-title">URANUS , NEPTUNUS.</h5>
                <p class="card-text">
                  Uranus dan Neptunus adalah dua planet terjauh dari Matahari sebagai pusat tata surya. Kedua planet 
                   tersebut adalah 
                  memiliki warna biru yang serupa untuk penampilannya, dan sering kali dijuluki sebagai raksasa es.
                </p>
              </div>
            </div>
        </div>
      </div>
    </div>
```
## Tentang 
```
<div class="container-fluid pt-5 pb-5">
      <div class="container">
        <h2 class="display-3 text-center" id="tentang">Tentang</h2>
        <p class="text-center">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea, ex!
        </p>
        <div class="clearfix pt-5">
          <img
            src="gambar/mp.jfif"
            class="col-md-6 float-md-end mb-3 crop-img"
            width="300"
            height="300"
          />
          <p>
            Planet adalah benda angkasa yang tidak memiliki cahaya nya sendiri. 
            Planet adalah benda angkasa yang memiliki bentuk seperti bulatan. 
            Planet-planet yang ada di tata surya bergerak mengelilingi sebuah bintang.
             Bintang yang dikelilingi oleh para planet adalah matahari.
          </p>
          <p>
            Teori yang saat ini mendominasi adalah planet terbentuk saat sebuah nebula
             berubah menjadi cakram gas dan debu tipis. 
            Sebuah protobintang terbentuk di intinya dan dikelilingi oleh cakram protoplanet yang berputar.
          </p>
          <p>
            macam macam planet 
            <ol>
              <li>Merkurius</li>
              <li>Venus </li>
              <li>Bumi</li>
              <li>Mars</li>
              <li>Jupiter</li>
              <li>Sartunus</li>
              <li>Uranus</li>
              <li>Neptunus</li>
              
            </ol>
          </p>
          <p>
            Bumi dan tiga planet bagian dalam lainnya di tata surya kita (Merkurius, Venus, dan Mars)
           terbuat dari batu, mengandung mineral umum seperti feldspar dan logam seperti magnesium dan aluminium .
            Begitu pula Pluto. Planet-planet lainnya tidak padat. 
            Jupiter, misalnya, sebagian besar terdiri dari helium, hidrogen, dan air yang terperangkap.
          </p>
        </div>
      </div>
    </div>
```
## Tim
```
<div class="container-fluid pt-5 pb-5 bg-light">
      <div class="container text-center">
        <h2 class="display-3" id="staff">Tim Kami</h2>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et deleniti
          quas at magni, iusto voluptates neque corrupti dolorum! Repellat,
          quod.
        </p>
        <div class="row pt-4 gx-4 gy-4">
          <div class="col-md-4 text-center tim">
            <img
              src="gambar/y4.jfif"
              class="rounded-circle mb-3"
            />
            <h4>Putri</h4>
            <p>Programing web</p>
            <p>
              <a href="" class="social"><i class="fab fa-twitter"></i></a>
              <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
              <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
            </p>
          </div>
          <div class="col-md-4 text-center tim">
            <img
              src="gambar/y2.jfif"
              class="rounded-circle mb-3"
            />
            <h4>Maesha</h4>
            <p>editing</p>
            <p>
              <a href="" class="social"><i class="fab fa-twitter"></i></a>
              <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
              <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
            </p>
          </div>
          <div class="col-md-4 text-center tim">
            <img
              src="gambar/y3.jfif"
              class="rounded-circle mb-3"
            />
            <h4>citra</h4>
            <p>Network Engineer</p>
            <p>
              <a href="" class="social"><i class="fab fa-twitter"></i></a>
              <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
              <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
            </p>
          </div>
        </div>
      </div>
    </div>
```
## client
```
<div class="container-fluid client pt-5 pb-5">
      <div class="container text-center">
        <div class="row pt-4 gx-4 gy-4">
          <div class="col">
            <img
              src="https://cdn.iconscout.com/icon/free/png-256/microsoft-28-761688.png"
            />
          </div>
          <div class="col">
            <img
              src="https://cdn3.iconfinder.com/data/icons/glypho-social-and-other-logos/64/logo-facebook-512.png"
            />
          </div>
          <div class="col">
            <img src="https://image.flaticon.com/icons/png/512/61/61109.png" />
          </div>
          <div class="col">
            <img
              src="https://i.pinimg.com/originals/20/1d/17/201d17590b3a7bc8939ca37e577bbbd8.png"
            />
          </div>
          <div class="col">
            <img
              src="https://www.ictmagazine.nl/wp-content/uploads/2020/10/ibm-720x340-1.png"
            />
          </div>
        </div>
      </div>
    </div>
```
## Kontak
```
<div class="container-fluid pt-5 pb-5 kontak">
      <div class="container">
        <h2 class="display-3 text-center" id="kontak">Kontak Kami</h2>
        <p class="text-center">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque, porro.
        </p>
        <div class="row pb-3">
          <div class="col-md-6">
            <input
              class="form-control form-control-lg mb-3"
              type="text"
              placeholder="Nama"
            />
            <input
              class="form-control form-control-lg mb-3"
              type="text"
              placeholder="Email"
            />
            <input
              class="form-control form-control-lg"
              type="text"
              placeholder="No. Phone"
            />
          </div>
          <div class="col-md-6">
            <textarea class="form-control form-control-lg" rows="5"></textarea>
          </div>
        </div>
        <div class="col-md-3 mx-auto text-center">
          <button type="button" class="btn btn-danger btn-lg">
            Kirim Pesan
          </button>
        </div>
      </div>
    </div>
    <div class="container text-center pt-5 pb-5">
      PUTRI YANTI &copy; 2024
    </div>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
```



