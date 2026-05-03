<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animación de Imagen</title>
    <style>
        body {
            margin: 0;
            padding: 0;
        }
        @keyframes waveMove {
            0% {
                background-position-x: 0;
            }
            100% {
                background-position-x: -200px;
            }
        }
        .container {
            background-image: url(https://www.ongi.com.mx/Assets/Wave.svg);
            background-repeat: repeat-x;
            background-size: auto 150px;
            animation: waveMove 3s linear infinite;
            text-align: center;
            padding: 100px 0;
            position: relative;
            min-height: 200px;
        }
        .text-below {
            position: relative;
            z-index: 1;
            margin-top: 20px;
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="text-below">Hi there 👋</h1>
    </div>
</body>
</html>
