<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>¿Quieres ser mi novia?</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 50px;
            background-color: #ffe6f0;
        }
        button {
            font-size: 20px;
            padding: 15px 30px;
            background-color: #ff66b2;
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff3385;
        }
        h1 {
            color: #ff3385;
        }
    </style>
</head>
<body>

    <h1 id="pregunta">¿Quieres ser mi novia?</h1>
    <button onclick="responder()">Sí</button>

    <script>
        function responder() {
            document.getElementById('pregunta').innerText = "¡Eso ya lo sabía! Te quiero mucho ❤️";
        }
    </script>

</body>
</html>
