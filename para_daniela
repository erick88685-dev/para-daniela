<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Destellos de Amor</title>
    <style>
        body {
            background-color: #000;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
            font-family: Arial, sans-serif;
            color: #fff;
            text-align: center;
            /* Fondo de pantalla de corazones */
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" opacity="0.1"><path fill="%23e60073" d="M50 85L50 85c-15-15-20-25-20-35c0-10 10-20 20-20s20 10 20 20c0 10-5 20-20 35z" transform="scale(0.5) translate(-10 -10)" /><path fill="%23ff4da6" d="M50 85L50 85c-15-15-20-25-20-35c0-10 10-20 20-20s20 10 20 20c0 10-5 20-20 35z" transform="scale(0.4) translate(10 10)" /></svg>');
            background-size: 80px 80px;
            animation: moveHearts 20s linear infinite;
        }

        @keyframes moveHearts {
            from {
                background-position: 0 0;
            }
            to {
                background-position: 100% 100%;
            }
        }

        .container {
            position: relative;
        }

        .text {
            font-size: 4em; /* Reducido para que quepa todo en una línea */
            font-weight: bold;
            color: #fff;
            text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #e60073, 0 0 40px #e60073, 0 0 50px #e60073, 0 0 60px #e60073, 0 0 70px #e60073;
            animation: glow 1.5s ease-in-out infinite alternate;
            z-index: 1;
        }

        .heart {
            font-size: 8em;
            color: #ff0000;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            animation: pulse 1s infinite;
            z-index: 0;
        }

        @keyframes glow {
            from {
                text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #e60073, 0 0 40px #e60073;
            }
            to {
                text-shadow: 0 0 20px #fff, 0 0 30px #ff4da6, 0 0 40px #ff4da6, 0 0 50px #ff4da6, 0 0 60px #ff4da6, 0 0 70px #ff4da6;
            }
        }

        @keyframes pulse {
            0% {
                transform: translate(-50%, -50%) scale(1);
                opacity: 0.7;
            }
            50% {
                transform: translate(-50%, -50%) scale(1.1);
                opacity: 1;
            }
            100% {
                transform: translate(-50%, -50%) scale(1);
                opacity: 0.7;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="heart"></div>
        <div class="text">Te Amo Daniela ❤️</div>
    </div>
</body>
</html>
