<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Galeri Pribadi</title>

<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:#0f172a;
color:white;
}

header{
height:70vh;
background:linear-gradient(
rgba(0,0,0,.5),
rgba(0,0,0,.7)),
url('https://images.unsplash.com/photo-1506744038136-46273834b3fb');
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
}

.hero{
max-width:700px;
padding:20px;
}

.hero h1{
font-size:60px;
margin-bottom:15px;
}

.hero p{
font-size:20px;
opacity:.9;
}

.container{
max-width:1200px;
margin:auto;
padding:50px 20px;
}

.section-title{
font-size:35px;
margin-bottom:25px;
}

.gallery{
display:grid;
grid-template-columns:
repeat(auto-fill,minmax(280px,1fr));
gap:20px;
}

.card{
background:#1e293b;
border-radius:20px;
overflow:hidden;
transition:.3s;
cursor:pointer;
}

.card:hover{
transform:translateY(-8px);
}

.card img,
.card video{
width:100%;
height:300px;
object-fit:cover;
display:block;
}

.info{
padding:15px;
}

.info h3{
margin-bottom:8px;
}

.info p{
color:#cbd5e1;
font-size:14px;
}

footer{
padding:30px;
text-align:center;
background:#020617;
margin-top:50px;
}

.btn{
display:inline-block;
margin-top:20px;
padding:12px 30px;
background:#ff4458;
color:white;
text-decoration:none;
border-radius:50px;
font-weight:bold;
}

.btn:hover{
background:#ff2d45;
}

</style>
</head>
<body>

<header>
<div class="hero">
<h1>Galeri Pribadi</h1>
<p>Simpan momen terbaik dalam foto dan video.</p>

<a href="#galeri" class="btn">
Lihat Galeri
</a>

</div>
</header>

<div class="container" id="galeri">

<h2 class="section-title">
📸 Foto & Video
</h2>

<div class="gallery">

<div class="card">
<img src="foto1.jpg">
<div class="info">
<h3>Liburan Pantai</h3>
<p>12 Januari 2026</p>
</div>
</div>

<div class="card">
<img src="foto2.jpg">
<div class="info">
<h3>Family Time</h3>
<p>25 Februari 2026</p>
</div>
</div>

<div class="card">
<video controls>
<source src="video1.mp4">
</video>
<div class="info">
<h3>Video Kenangan</h3>
<p>Durasi 1:25</p>
</div>
</div>

<div class="card">
<img src="foto3.jpg">
<div class="info">
<h3>Sunset</h3>
<p>Pekalongan</p>
</div>
</div>

<div class="card">
<video controls>
<source src="video2.mp4">
</video>
<div class="info">
<h3>Perjalanan</h3>
<p>Video HD</p>
</div>
</div>

<div class="card">
<img src="foto4.jpg">
<div class="info">
<h3>Momen Terbaik</h3>
<p>Koleksi Pribadi</p>
</div>
</div>

</div>

</div>

<footer>
© 2026 Galeri Pribadi
</footer>

</body>
</html>
