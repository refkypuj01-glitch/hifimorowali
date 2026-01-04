<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>HiFi Air – Internet Rumah Cepat & Stabil</title>

<style>
:root {
  --yellow:#FDB813;
  --pink:#EC2C7C;
  --pink-dark:#C81E5A;
  --white:#FFFFFF;
  --text:#222;
  --gray-light:#f8f8f8;
}

/* GLOBAL RESET */
*{margin:0;padding:0;box-sizing:border-box;font-family:Courier;}
body{color:var(--text);background:var(--gray-light);line-height:1.6;}

/* BUTTONS */
.btn-primary {
  display:inline-block;
  padding:14px 28px;
  background:var(--pink);
  color:var(--white);
  border-radius:40px;
  font-weight:Helvetica;
  text-decoration:none;
  transition:0.3s;
 
.btn-primary2
  display:inline-block
  background:var(--yellow);
  color:var(--white);
  border-radius:40px;
  text-decoration:none;
  transition:0.3s;
  
  
}
.btn-primary:hover{background:var(--pink-dark);}

/* CONTAINER */
.container{max-width:1200px;margin:auto;padding:20px;}

/* HERO */
.hero {
  background:var(--yellow);
  padding:80px 20px;
  text-align:center;
  color:var(--white);
}
.hero h1{font-size:3rem; margin-bottom:08px;}
.hero p{font-size:1.2rem; margin-bottom:20px;}
.hero img{max-width:400px; width:100%; margin-top:20px;}

/* FEATURES */
.features{display:flex;flex-wrap:wrap; gap:20px; margin:60px 0; justify-content:space-evenly;}
.feature-item {
  background:var(--white);
  flex:1 1 250px;
  padding:20px;
  border-radius:18px;
  box-shadow:0 4px 12px rgba(0,0,0,0.1);
}
.feature-item h3{color:var(--pink); margin-bottom:12px;}
.feature-item p{font-size:0.95rem;}

/* PACKAGES */
.pricing{background:var(--white);padding:60px 20px;border-radius:20px;box-shadow:0 4px 16px rgba(0,0,0,0.1);}
.pricing h2{text-align:center;color:var(--pink);margin-bottom:24px;}
.plan-cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:20px;}
.plan {
  background:var(--yellow);
  padding:18px;
  border-radius:16px;
  text-align:center;
  font-weight:Arial;
}
.plan h3{font-size:1.4rem;color:var(--pink);}
.plan p{font-size:1.1rem; margin-top:8px;}

/* TESTIMONIALS */
.testimonials{margin:60px 0;}
.testimonials h2{text-align:center;color:var(--pink); margin-bottom:24px;}
.testimonial-card {
  background:var(--white);
  padding:24px;
  border-radius:16px;
  box-shadow:0 4px 12px rgba(0,0,0,0.08);
  margin:0 10px;
}
.testimonial-card p{font-size:0.95rem; margin-bottom:12px;}
.testimonial-card span{font-weight:bold; color:var(--pink);}

/* CTA BIG */
.cta-big{text-align:center; padding:60px 20px; background:var(--pink); color:var(--white);}
.cta-big h2{font-size:2rem; margin-bottom:16px;}

/* FOOTER */
footer{text-align:center; padding:28px 10px; font-size:0.9rem;}
footer a{color:var(--pink); text-decoration:none;}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
    <h1>HiFi Air Starter Kit</h1>
    <p>Internet Rumah Cepat, Stabil & Tanpa Kabel</p>
    <a href="#packages" class="btn-primary">Isi Ulang Paket HiFi</a>
    <p><a href="#order" class="BUTTONS"> Beli Router</a></p>
</section>

<div class="container">

  <!-- FEATURES -->
  <section class="features">
    <div class="feature-item">
      <h3>📶 Sinyal Kuat & Luas</h3>
      <p>Jaringan kuat yang stabil di seluruh rumah untuk streaming, kerja dan belajar tanpa lag.</p>
    </div>
    <div class="feature-item">
      <h3>🏠 Tanpa Kabel</h3>
      <p>Siap digunakan tanpa instalasi rumit — cukup pasang dan langsung online.</p>
    </div>
    <div class="feature-item">
      <h3>👨‍👩‍👧 Untuk Semua Perangkat</h3>
      <p>Mendukung multi-device: HP, laptop, TV & game tanpa gangguan.</p>
    </div>
  </section>

  <!-- PRICING PACKAGES -->
  <section class="pricing" id="packages">
    <h2>Pilihan Kuota Paket</h2>
    <div class="plan-cards">
      <a href="https://wa.me/6282248117262?text=Halo%20Admin%2C%20saya%20ingin%20order%20paket%20HiFi%20Air%20yang%2075%20GB%2C%20ini%20nomor%20HiFi%20saya:
"
        class="plan"+"btn-primary"><h3>75GB</h3><p>Rp75.000 / 30 hari</p></a>
      <a href="https://wa.me/6282248117262?text=Halo%20Admin%2C%20saya%20ingin%20order%20paket%20HiFi%20Air%20yang%20125%20GB%2C%20ini%20nomor%20HiFi%20saya:"
        class="plan"+"btn-primary"><h3>125GB</h3><p>Rp100.000 / 30 hari</p></a>
      <a href="https://wa.me/6282248117262?text=Halo%20Admin%2C%20saya%20ingin%20order%20paket%20HiFi%20Air%20yang%20200%20GB%2C%20ini%20nomor%20HiFi%20saya:"
        class="plan"><h3>200GB</h3><p>Rp150.000 / 30 hari</p></a>
      <a href="https://wa.me/6282248117262?text=Halo%20Admin%2C%20saya%20ingin%20order%20paket%20HiFi%20Air%20yang%20500%20GB%2C%20ini%20nomor%20HiFi%20saya:"
        class="plan"><h3>500GB</h3><p>Rp250.000 / 30 hari</p></a>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section class="testimonials">
    <h2>Apa Kata Pelanggan</h2>
    <div class="testimonial-card">
      <p>"Internet lancar terus, kerja di rumah & streaming tanpa putus!"</p>
      <span>— Fitri, Jakarta</span>
    </div>
    <div class="testimonial-card">
      <p>"Routernya cepat nyambung, semua perangkat aman tanpa buffering."</p>
      <span>— Dedi, Bandung</span>
    </div>
    <div class="testimonial-card">
      <p>"50GB kuota bonus bikin internet makin hemat tiap bulan!"</p>
      <span>— Sinta, Surabaya</span>
    </div>
  </section>

</div>

<!-- CTA LARGE -->
<section class="cta-big" id="order">
  <h2>Siap Online Sekarang?</h2>
  <a href="https://wa.me/6282248117262" class="btn-primary2">Chat WhatsApp Sekarang</a>
</section>

<!-- FOOTER -->
<footer>
  © 2026 HiFi Air • Sosial Media: <a href="https://www.instagram.com/hifiair.mrw?igsh=amE3bDFkazYxZHBy">klik di sini</a>
</footer>

</body>
</html>
