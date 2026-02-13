<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Congreso Juvenil 2026 | Unión Juvenil Evangélica del Caribe</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<link rel="icon" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS6wUNyKE5Inn-HQCu-8bcSf8TNP8z91gqCeQ&s" type="image/x-icon">
<link rel="stylesheet" href="style.css">
<style>
*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{font-family:'Poppins',sans-serif;color:#333;line-height:1.6;position:relative;}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    color: #333;
    line-height: 1.6;
}

/* HERO */
.hero {
    background: linear-gradient(135deg, #1e3c72, #2a5298);
    color: white;
    height: 90vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 20px;
}

.hero h1 {
    font-size: 3rem;
    font-weight: 700;
}

.hero p {
    margin: 20px 0;
    font-size: 1.2rem;
}

.btn-primary {
    background: #ff7a18;
    color: white;
    padding: 12px 30px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: 600;
    transition: 0.3s ease;
}

.btn-primary:hover {
    background: #ff9a44;
}

/* BENEFICIOS */
.beneficios {
    padding: 80px 20px;
    text-align: center;
    background: #f4f7fb;
}

.beneficios h2 {
    margin-bottom: 40px;
    font-size: 2rem;
}

.cards {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}

.card {
    background: white;
    padding: 30px;
    width: 280px;
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.08);
    transition: 0.3s ease;
}

.card:hover {
    transform: translateY(-10px);
}

/* FORM */
.form-section {
    padding: 80px 20px;
    text-align: center;
}

.form-section h2 {
    margin-bottom: 40px;
    font-size: 2rem;
}

iframe {
    width: 100%;
    max-width: 800px;
    height: 900px;
    border: none;
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}

/* FOOTER */
footer {
    background: #1e3c72;
    color: white;
    text-align: center;
    padding: 20px;
}

/* RESPONSIVE */
@media (max-width: 768px) {
    .hero h1 {
        font-size: 2.2rem;
    }

    .cards {
        flex-direction: column;
        align-items: center;
    }

    iframe {
        height: 1000px;
    }
}
/* ===== CARRUSEL ===== */
.galeria{
    padding:70px 20px;
    background:#ffffff;
    text-align:center;
}

.galeria h2{
    font-size:2rem;
    margin-bottom:40px;
}

.carousel{
    position:relative;
    max-width:1000px;
    margin:auto;
    overflow:hidden;
}

.carousel-track{
    display:flex;
    transition:transform .6s ease;
}

.carousel-track img{
    width:100%;
    max-width:1000px;
    height:450px;
    object-fit:cover;
    border-radius:14px;
    flex-shrink:0;
    padding:0 10px;
}

/* botones */
.carousel button{
    position:absolute;
    top:50%;
    transform:translateY(-50%);
    background:rgba(0,0,0,0.5);
    border:none;
    color:white;
    font-size:30px;
    padding:10px 15px;
    cursor:pointer;
    border-radius:50%;
    z-index:10;
    transition:.3s;
}

.carousel button:hover{
    background:#f39c12;
}

.prev{left:10px;}
.next{right:10px;}

/* responsive */
@media(max-width:768px){
    .carousel-track img{
        height:250px;
    }
}


/* NAVBAR */
.navbar{position:fixed;width:100%;top:0;display:flex;justify-content:space-between;align-items:center;padding:10px 40px;background:rgba(20,30,70,0.95);backdrop-filter:blur(8px);color:white;z-index:1000;}
.logo-container{display:flex;align-items:center;gap:10px;}
.logo-container img{height:45px;}
.logo-text{font-weight:600;font-size:0.9rem;}
.nav-btn{background:#f39c12;padding:8px 20px;border-radius:50px;text-decoration:none;color:white;transition:0.3s;font-weight:500;}
.nav-btn:hover{background:#ffb347;}

/* HERO CON BANNER AJUSTADO */
.hero{
    margin-top:80px;
    background: url('img/banner.jpg') center center/cover no-repeat;
    min-height:95vh;
    color:white;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:20px;
    position:relative;
}
.hero::before{
    content:'';
    position:absolute;
    inset:0;
    background: rgb(235, 36, 36);
    image-resolution: from-image;
    background: linear-gradient(90deg, rgba(235, 36, 36, 0.8) 0%, rgba(20, 30, 70, 0.8) 100%);
    touch-action: cross-slide-x;
    z-index:0;
}
.hero-content{
    position:relative;
    z-index:1;
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    gap:15px;
}
.hero-content img{
    height:120px;
    max-width:200px;
}
.hero h1{
    font-size:3rem;
    font-weight:700;
    line-height:1.2;
    margin:10px 0;
}
.hero p{
    font-size:1.3rem;
    margin-bottom:20px;
}
.btn-primary{
    background:#f39c12;
    color:white;
    padding:14px 35px;
    border-radius:50px;
    text-decoration:none;
    font-weight:600;
    transition:0.3s ease;
}
.btn-primary:hover{background:#ffb347;}

/* CONTADOR */
.countdown{
    display:flex;
    justify-content:center;
    gap:20px;
    margin-top:20px;
    font-size:1.2rem;
    font-weight:600;
    flex-wrap:wrap;
}
.countdown div{
    background:rgba(255,255,255,0.2);
    padding:10px 15px;
    border-radius:10px;
    min-width:60px;
    color:white;
}

/* INFO */
.info{padding:60px 20px;text-align:center;background:#f4f7fb;}
.info h2{margin-bottom:20px;font-size:2rem;}
.info p{max-width:700px;margin:auto;margin-bottom:10px;}

/* INVITADOS */
.invitados{padding:60px 20px;text-align:center;background:#e9eef5;}
.invitados h2{margin-bottom:40px;font-size:2rem;}
.cards{display:flex;justify-content:center;gap:30px;flex-wrap:wrap;}
.card{background:white;padding:20px;width:220px;border-radius:12px;box-shadow:0 10px 25px rgba(0,0,0,0.08);transition:0.3s ease;}
.card img{width:100%;border-radius:12px;margin-bottom:15px;}
.card h3{font-size:1.1rem;margin-bottom:5px;}
.card p{font-size:0.95rem;color:#555;}
.card:hover{transform:translateY(-8px);box-shadow:0 15px 35px rgba(0,0,0,0.12);}

/* FORM */
.form-section{padding:80px 20px;text-align:center;}
.form-section h2{margin-bottom:40px;font-size:2rem;}
iframe{width:100%;max-width:800px;height:900px;border:none;border-radius:12px;box-shadow:0 10px 30px rgba(0,0,0,0.1);}

/* FOOTER */
footer{background:#0f2027;color:white;text-align:center;padding:20px;}

/* WHATSAPP FLOTANTE */
.whatsapp-float{position:fixed;bottom:20px;right:20px;z-index:1000;}
.whatsapp-float a{display:flex;align-items:center;justify-content:center;width:60px;height:60px;background:#25D366;color:white;border-radius:50%;box-shadow:0 4px 12px rgba(0,0,0,0.3);text-decoration:none;font-size:30px;transition:0.3s;}
.whatsapp-float a:hover{background:#1ebe57;}

/* RESPONSIVE */
@media(max-width:1024px){
    .hero h1{font-size:2.5rem;}
    .hero p{font-size:1.1rem;}
    .hero-content img{height:100px;}
}
@media(max-width:768px){
    .hero h1{font-size:2rem;}
    .hero p{font-size:1rem;}
    .hero-content img{height:80px;}
    .countdown{flex-direction:column;gap:10px;}
}
</style>
</head>

<body>

<!-- Música de bienvenida -->
<audio controls autoplay loop style="position:fixed;bottom:10px;left:10px;z-index:1000;">
<source src="audio/" type="audio/mpeg">Tu navegador no soporta audio.
</audio>

<!-- NAVBAR -->
<nav class="navbar">
    <div class="logo-container">
        <img src="img/png_20230111_102718_0000.png">
        <div class="logo-text">Unión Juvenil Evangélica del Caribe</div>
    </div>
    <a href="#formulario" class="nav-btn">Inscribirme</a>
</nav>


<!-- HERO -->
 
<header class="hero">
    
    <div class="hero-content">
        <img src="img/png_20230111_102718_0000.png" alt="" srcset="">
        <h1>Congreso Juvenil 2026</h1>
        <p>Circuito 2 - Zona 6</p>
        <div class="countdown" id="countdown">
            <div><span id="days">0</span><br>Días</div>
            <div><span id="hours">0</span><br>Horas</div>
            <div><span id="minutes">0</span><br>Minutos</div>
            <div><span id="seconds">0</span><br>Segundos</div>
        </div>
        <a href="#formulario" class="btn-primary">Preinscribirme ahora</a>
    </div>
    
</header>

<!-- INFO -->
<section class="info">
<h2>Un Encuentro que Transformará tu Vida</h2>
<p>📅 Fecha: 15-17 de Julio 2026</p>
<p>📍 Ubicación: Salón Central, Circuito 2 Zona 6, Caribe</p>
<p>Un tiempo especial de adoración, palabra y crecimiento espiritual. Este congreso ha sido preparado para fortalecer tu fe y activar tu propósito.</p>
</section>

<!-- INVITADOS -->
<section class="invitados">
<h2>🎤 Invitados Especiales</h2>
<div class="cards">
    <div class="card">
        <img src="https://via.placeholder.com/220x150" alt="Invitado 1">
        <h3>Pastor Juan Pérez</h3>
        <p>Orador principal y guía espiritual.</p>
    </div>
    <div class="card">
        <img src="https://via.placeholder.com/220x150" alt="Invitado 2">
        <h3>Pastora María López</h3>
        <p>Taller de liderazgo juvenil.</p>
    </div>
    <div class="card">
        <img src="https://via.placeholder.com/220x150" alt="Invitado 3">
        <h3>Grupo Musical Luz</h3>
        <p>Adoración y música en vivo.</p>
    </div>
</div>
</section>

<!-- FORMULARIO -->
<section id="formulario" class="form-section">
<h2>Formulario de Preinscripción</h2>
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfJeRfjRysZH4qcuW61IkezIdhXQoBJrIFlZGjjLMLj6QoccQ/viewform?embedded=true" loading="lazy">
Cargando…
</iframe>
</section>

<footer>
<p>© 2026 - Unión Juvenil Evangélica del Caribe | Circuito 2 Zona 6</p>
</footer>

<!-- WhatsApp flotante -->
<div class="whatsapp-float">
    <a href="https://wa.me/1234567890" target="_blank" title="Contactar por WhatsApp">📱</a>
</div>

<script>
// Contador regresivo
const countdownDate = new Date("d, 2026 09:00:00").getTime();
const daysEl = document.getElementById("days");
const hoursEl = document.getElementById("hours");
const minutesEl = document.getElementById("minutes");
const secondsEl = document.getElementById("seconds");

setInterval(()=>{
    const now = new Date().getTime();
    const distance = countdownDate - now;
    const days = Math.floor(distance / (1000*60*60*24));
    const hours = Math.floor((distance%(1000*60*60*24))/(1000*60*60));
    const minutes = Math.floor((distance%(1000*60*60))/(1000*60));
    const seconds = Math.floor((distance%(1000*60))/1000);
    daysEl.innerText=days;
    hoursEl.innerText=hours;
    minutesEl.innerText=minutes;
    secondsEl.innerText=seconds;
},1000);
</script>
<script>
const track = document.querySelector('.carousel-track');
const slides = document.querySelectorAll('.carousel-track img');
const nextBtn = document.querySelector('.next');
const prevBtn = document.querySelector('.prev');

let index = 0;

function updateCarousel(){
    track.style.transform = `translateX(-${index * 100}%)`;
}

nextBtn.addEventListener('click',()=>{
    index++;
    if(index >= slides.length) index = 0;
    updateCarousel();
});

prevBtn.addEventListener('click',()=>{
    index--;
    if(index < 0) index = slides.length - 1;
    updateCarousel();
});

/* autoplay */
setInterval(()=>{
    index++;
    if(index >= slides.length) index = 0;
    updateCarousel();
},5000);
</script>

</body>
</html>
