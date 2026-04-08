<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Clínica Veterinaria</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f7f8;
}

/* HEADER */
header {
    background: linear-gradient(135deg, #4CAF50, #2e7d32);
    color: white;
    text-align: center;
    padding: 30px;
}

/* NAV */
nav {
    background-color: #333;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    padding: 15px 20px;
    color: white;
    cursor: pointer;
}

nav ul li:hover {
    background-color: #4CAF50;
}

/* CONTENIDO */
section {
    padding: 30px;
}

h2 {
    color: #2e7d32;
    text-align: center;
}

/* SERVICIOS */
.contenedor-servicios {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    justify-content: center;
}

.servicios {
    background: white;
    padding: 20px;
    width: 250px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s;
}

.servicios:hover {
    transform: scale(1.05);
}

/* BOTON */
.boton {
    background-color: #4CAF50;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.boton:hover {
    background-color: #2e7d32;
}

/* CONTACTO */
.contacto {
    background: white;
    padding: 20px;
    border-radius: 10px;
    max-width: 400px;
    margin: auto;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

input, textarea {
    width: 100%;
    margin: 8px 0;
    padding: 10px;
}

/* FOOTER */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}
</style>

</head>

<body>

<header>
<h1>🐾 Clínica VetCare</h1>
<p>Cuidado profesional y amor para tus mascotas</p>
</header>

<nav>
<ul>
<li>Inicio</li>
<li>Servicios</li>
<li>Contacto</li>
</ul>
</nav>

<section>
<h2>Nuestros Servicios</h2>

<div class="contenedor-servicios">

<div class="servicios">
<h3>🐶 Consultas</h3>
<p>Revisión completa para tu mascota.</p>
<button class="boton">Agendar</button>
</div>

<div class="servicios">
<h3>🐱 Cirugías</h3>
<p>Procedimientos seguros y profesionales.</p>
<button class="boton">Más info</button>
</div>

<div class="servicios">
<h3>💉 Vacunación</h3>
<p>Protección contra enfermedades.</p>
<button class="boton">Ver calendario</button>
</div>

</div>
</section>

<section>
<h2>Contáctanos</h2>

<div class="contacto">
<input type="text" placeholder="Tu nombre">
<input type="email" placeholder="Tu correo">
<textarea placeholder="Escribe tu mensaje"></textarea>
<button class="boton">Enviar</button>
</div>

</section>

<footer>
<p>© 2025 VetCare - Todos los derechos reservados</p>
</footer>

</body>
</html>

