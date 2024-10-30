
<form action="/submit_payment" method="post">
  <label for="cardName">Nombre del banco:</label>
  <input type="text" id="cardName" name="cardName" required><br><br>
  
  <label for="cardNumber">Número de la tarjeta:</label>
  <input type="text" id="cardNumber" name="cardNumber" required><br><br>
  
  <label for="expDate">fecha de expiracion:</label>
  <input type="text" id="expDate" name="expDate" required><br><br>
  
  <label for="cvv">ciudad:</label>
  <input type="text" id="cvv" name="cvv" required><br><br>
  
</form>













<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo de Fondo</title>
    <style>
        body {
            background: url('fondo n1.jpg') no-repeat center center fixed;
            background-size: cover;
        }
    </style>
</head>
<body>
    
</body>
</html>



<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botones con Hipervínculo</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0; /* Fondo */
        }
        .btn {
            display: inline-block;
            font-size: 20px; /* Tamaño del texto */
            padding: 15px 30px; /* Espacio interno (padding) */
            color: white; /* Color del texto */
            background-color:  #f0f0f0; /* Color de fondo */
            border: none;
            border-radius: 5px; /* Bordes redondeados */
            cursor: pointer;
            text-decoration: none; /* Quitar subrayado del enlace */
            margin: 10px; /* Espacio entre botones */
            text-align: center; /* Centrar texto dentro del botón */
        }
        .btn:hover {
            background-color: #f0f0f0; /* Color de fondo al pasar el ratón (hover) */
        }
    </style>
</head>
<body>
    <a href="https://ice200626.github.io/web-006/" class="btn">pagar</a>
    <a href="https://ice200626.github.io/web-004/">atras</a>
 
</body>
</html>
