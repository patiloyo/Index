<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Negocio Inclusivo Accesible</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 20px;
            background-color: #fff;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        h2 {
            color: #333;
        }
        /* Responsividad para dispositivos móviles */
        @media screen and (max-width: 768px) {
            nav ul {
                display: block;
            }
            nav ul li {
                display: block;
                margin: 10px 0;
            }
        }
        /* Enlaces enfocados para accesibilidad */
        a:focus {
            outline: 2px solid #ffbf00;
            background-color: #333;
        }
        /* Formularios accesibles */
        label {
            font-weight: bold;
        }
        input[type="text"], input[type="email"] {
            padding: 8px;
            margin-top: 5px;
            width: 100%;
            box-sizing: border-box;
        }
        input[type="submit"] {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
        }
        input[type="submit"]:focus {
            outline: 2px solid #ffbf00;
        }
    </style>
</head>
<body>
    <header>
        <h1>Negocio Inclusivo Accesible</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#quienes-somos">Quiénes Somos</a></li>
            <li><a href="#productos">Productos y Servicios</a></li>
            <li><a href="#modelos-pago">Modelos de Pago</a></li>
            <li><a href="#escalabilidad">Escalabilidad</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <section id="inicio">
        <h2>Inicio</h2>
        <p>Bienvenido a nuestro negocio inclusivo, dedicado a mejorar la calidad de vida de las personas con discapacidades físicas y sensoriales. Ofrecemos productos accesibles y servicios personalizados para facilitar la vida diaria y fomentar la autonomía.</p>
    </section>

    <section id="quienes-somos">
        <h2>Quiénes Somos</h2>
        <p>Nos especializamos en crear soluciones adaptadas para personas con discapacidades. Nuestro objetivo es eliminar barreras de accesibilidad, ofreciendo productos que ayuden a nuestros usuarios a llevar una vida más independiente y digna.</p>
    </section>

    <section id="productos">
        <h2>Productos y Servicios</h2>
        <ul>
            <li>Tienda en línea accesible con herramientas de navegación adaptadas.</li>
            <li>Asesoría personalizada para encontrar los productos que mejor se ajusten a tus necesidades.</li>
            <li>Capacitación sobre el uso de nuestros productos para maximizar su utilidad.</li>
            <li>Comunidad en línea para compartir experiencias y obtener apoyo.</li>
        </ul>
    </section>

    <section id="modelos-pago">
        <h2>Modelos de Pago</h2>
        <p>Ofrecemos varios métodos de pago y suscripciones que permiten acceso continuo a nuestros productos y servicios. Además, puedes beneficiarte de nuestros planes de asesoría personalizada y capacitación.</p>
    </section>

    <section id="escalabilidad">
        <h2>Escalabilidad</h2>
        <p>Nuestro plan de crecimiento incluye la expansión a nivel nacional e internacional, así como la introducción de nuevas soluciones basadas en las necesidades de nuestros usuarios. Además, buscamos crear alianzas con organizaciones que promuevan la inclusión.</p>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <form action="#" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" aria-describedby="nombre-ayuda" required><br><br>
            <span id="nombre-ayuda">Por favor, ingresa tu nombre completo.</span>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" aria-describedby="email-ayuda" required><br><br>
            <span id="email-ayuda">Introduce un correo electrónico válido para que podamos contactarte.</span>

            <input type="submit" value="Enviar">
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Negocio Inclusivo. Todos los derechos reservados.</p>
    </footer>
</body>
</html>