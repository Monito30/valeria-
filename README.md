<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Web Básica</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #6200ea;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #3700b3;
            padding: 0.5rem;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 1rem;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            padding: 2rem;
        }
        footer {
            background-color: #6200ea;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a mi Página Web</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#sobre-mi">Sobre mí</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    <main>
        <section id="inicio">
            <h2>Inicio</h2>
            <p>Esta es una página web básica creada con HTML y CSS. Explora las secciones para aprender más.</p>
        </section>
        <section id="sobre-mi">
            <h2>Sobre mí</h2>
            <p>Hola, soy un desarrollador web en formación y esta es mi primera página web.</p>
        </section>
        <section id="contacto">
            <h2>Contacto</h2>
            <p>Puedes contactarme a través de mi correo electrónico: ejemplo@correo.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Mi Página Web. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
