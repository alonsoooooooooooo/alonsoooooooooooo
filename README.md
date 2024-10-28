<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flor con Nombre Aylen</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f8ff;
        }

        .flower {
            position: relative;
            width: 200px;
            height: 200px;
        }

        .petal {
            width: 80px;
            height: 120px;
            background-color: #ff69b4;
            border-radius: 50%;
            position: absolute;
            top: 40px;
            left: 60px;
            transform-origin: bottom center;
        }

        .petal:nth-child(1) { transform: rotate(0deg); }
        .petal:nth-child(2) { transform: rotate(45deg); }
        .petal:nth-child(3) { transform: rotate(90deg); }
        .petal:nth-child(4) { transform: rotate(135deg); }
        .petal:nth-child(5) { transform: rotate(180deg); }
        .petal:nth-child(6) { transform: rotate(225deg); }
        .petal:nth-child(7) { transform: rotate(270deg); }
        .petal:nth-child(8) { transform: rotate(315deg); }

        .center {
            width: 80px;
            height: 80px;
            background-color: #ffda00;
            border-radius: 50%;
            position: absolute;
            top: 60px;
            left: 60px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 18px;
            font-weight: bold;
            color: #333;
            text-transform: uppercase;
        }
    </style>
</head>
<body>
    <div class="flower">
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="center">Aylen</div>
    </div>
</body>
</html>
