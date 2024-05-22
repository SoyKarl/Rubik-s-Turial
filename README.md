# Rubik-s-Turial
tutoriales de cubos y divercion 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karl - Cubos Rubik</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77a8a8 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        #showcase {
            min-height: 400px;
            background: url('https://images.unsplash.com/photo-1531497865146-3d98c027e122') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        #showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        #showcase p {
            font-size: 20px;
        }
        #main {
            padding: 20px;
            background: #fff;
            color: #333;
        }
        .section {
            padding: 20px 0;
            border-bottom: #77a8a8 2px solid;
        }
        .section:last-child {
            border: none;
        }
        .section h2 {
            margin-top: 0;
        }
        .section p {
            line-height: 1.5em;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 30px 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span style="color: #77a8a8;">Karl</span> - Cubos Rubik</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#main">Inicio</a></li>
                    <li><a href="#tutorials">Tutoriales</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section id="showcase">
        <div class="container">
            <h1>Bienvenido a mi mundo de Cubos Rubik</h1>
            <p>Aprende y perfecciona tus habilidades con los cubos Rubik.</p>
        </div>
    </section>
    <div id="main" class="container">
        <section class="section" id="bio">
            <h2>Sobre mí</h2>
            <p>Hola, soy Karl, un entusiasta de los cubos Rubik. Aquí encontrarás tutoriales y recursos para mejorar tu técnica y disfrutar más de este fascinante pasatiempo.</p>
        </section>
        <section class="section" id="tutorials">
            <h2>Tutoriales</h2>
            <p>Encuentra aquí una variedad de tutoriales para diferentes niveles de habilidad, desde principiantes hasta expertos.</p>
            <ul>
                <li><a href="#">Tutorial Básico para Principiantes</a></li>
                <li><a href="#">Método Avanzado CFOP</a></li>
                <li><a href="#">Resolución de Cubo 4x4</a></li>
                <li><a href="#">Técnicas de Velocidad</a></li>
            </ul>
        </section>
    </div>
    <footer>
        <p>Karl &copy; 2024</p>
    </footer>
</body>
</html>
