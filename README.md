<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Divisiones en HTML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
        nav {
            background: #555;
            padding: 10px;
            text-align: center;
        }
        .container {
            display: flex;
            margin: 10px;
        }
        aside {
            width: 30%;
            background: #f4f4f4;
            padding: 10px;
        }
        section {
            flex: 1;
            background: #ddd;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Página Web</h1>
    </header>
    <nav>
        <a href="#">Inicio</a> | <a href="#">Sobre mí</a> | <a href="#">Contacto</a>
    </nav>
    <div class="container">
        <aside>
            <h2>Barra Lateral</h2>
            <p>Información adicional aquí.</p>
        </aside>
        <section>
            <h2>Contenido Principal</h2>
            <p>Aquí va el contenido principal de la página.</p>
        </section>
    </div>
    <footer>
        <p>© 2025 Mi Página Web</p>
    </footer>

</body>
</html>
