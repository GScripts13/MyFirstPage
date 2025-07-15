<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Te amo mucho mi amorcito</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #e6f2ff;
      text-align: center;
      padding: 50px;
    }

    h1 {
      color: #2c3e50;
    }

    p {
      font-size: 18px;
      color: #34495e;
    }

    button {
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #2980b9;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background-color: #1f6391;
    }
  </style>
</head>
<body>

  <h1>Te Amo</h1>
  <p id="mensaje">Esta es mi primera página web , y me gustaria dedicartela a ti porq enserio te amo mucho mi amorcito.</p>
  <button onclick="cambiarMensaje()">Haz clic aquí</button>

  <script>
    function cambiarMensaje() {
      document.getElementById("mensaje").innerText = "Amo pasar tiempo contigo mi vida";
    }
  </script>

</body>
</html>
