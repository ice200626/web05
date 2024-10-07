web
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Pago</title>
</head>
<body>
    <h2>Formulario de Pago</h2>
    <form action="/ruta_de_tu_servidor" method="POST">
        <label for="nombre">Nombre en la tarjeta:</label>
        <input type="text" id="nombre" name="nombre" required><br><br>

        <label for="tarjeta">Número de tarjeta:</label>
        <input type="text" id="tarjeta" name="tarjeta" required><br><br>

        <label for="fecha_expiracion">Fecha de expiración:</label>
        <input type="month" id="fecha_expiracion" name="fecha_expiracion" required><br><br>

        <label for="cvv">CVV:</label>
        <input type="text" id="cvv" name="cvv" required><br><br>

        <input type="submit" value="Pagar">
    </form>
</body>
</html>