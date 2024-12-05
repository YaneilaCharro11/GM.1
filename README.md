<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galería de Animales - Hipermedia</title>
    <style>
        /* Estilo global */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        main {
            padding: 20px;
        }
        .intro {
            text-align: center;
            margin-bottom: 30px;
        }
        .intro p {
            font-size: 18px;
            line-height: 1.6;
        }
        /* Galería */
        .galeria {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .item {
            width: 230px; /* Tamaño fijo para mantener el diseño uniforme */
            text-align: center;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .item:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
        }
        .item img {
            width: 100%; /* Mantiene proporción dentro de la tarjeta */
            max-width: 1024px; 
            height: auto;
            border-radius: 10px;
        }
        .item p {
            margin: 10px 0;
            font-weight: bold;
            color: #007BFF;
        }
        .item a {
            text-decoration: none;
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #007BFF;
            color: white;
            font-size: 14px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .item a:hover {
            background-color: #0056b3;
        }
        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- Encabezado -->
    <header>
        <h1>Galería de Animales</h1>
    </header>

    <!-- Contenido Principal -->
    <main>
        <!-- Introducción -->
        <section class="intro">
            <h2>Bienvenido a la Galería de Animales</h2>
            <p>
                Esta página presenta una galería de imágenes de diferentes animales. Explora la belleza del reino animal y descarga las imágenes que más te gusten.
            </p>
        </section>

        <!-- Galería -->
        <section class="galeria">
            <!-- Fila 1 -->
            <div class="item">
                <img src="tigre.jpg" alt="Tigre">
                <p>Tigre</p>
                <a href="tigre.jpg" download="Tigre">Descargar</a>
            </div>
            <div class="item">
                <img src="elefante.jpg" alt="Elefante">
                <p>Elefante</p>
                <a href="elefante.jpg" download="Elefante">Descargar</a>
            </div>
            <div class="item">
                <img src="bebe.jpg" alt="Panda">
                <p>Panda</p>
                <a href="panda.jpg" download="Panda">Descargar</a>
            </div>
            <div class="item">
                <img src="leon.jpg" alt="León">
                <p>León</p>
                <a href="leon.jpg" download="León">Descargar</a>
            </div>
            <!-- Fila 2 -->
            <div class="item">
                <img src="pad.jpg" alt="Jirafa">
                <p>Jirafa</p>
                <a href="Jirafa.jpg" download="Jirafa">Descargar</a>
            </div>
            <div class="item">
                <img src="coco.jpg" alt="Cocodrilo">
                <p>Cocodrilo</p>
                <a href="Cocodrilo.jpg" download="Cocodrilo">Descargar</a>
            </div>
            <div class="item">
                <img src="zorro.jpg" alt="Zorro">
                <p>Zorro</p>
                <a href="zorro.jpg" download="Zorro">Descargar</a>
            </div>
            <div class="item">
                <img src="koala.jpg" alt="Koala">
                <p>Koala</p>
                <a href="koala.jpg" download="Koala">Descargar</a>
            </div>
        </section>
    </main>

    <!-- Pie de página -->
    <footer>
        <p>&copy; 2024 - Creado por Yaneila Charro</p>
    </footer>
</body>
</html>
