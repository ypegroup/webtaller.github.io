<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taller de Canva - 12 de Diciembre</title>
    <style>
        body {margin:0;font-family:Arial,sans-serif;background:linear-gradient(135deg,#6a11cb 0%,#2575fc 100%);color:white;text-align:center;padding:40px 20px}
        .container {max-width:600px;margin:0 auto}
        h1 {font-size:4.5rem;margin:20px 0}
        .de {color:#00ff9d;font-size:5rem}
        .fecha {background:rgba(255,255,255,0.2);display:inline-block;padding:10px 20px;border-radius:50px;font-size:1.5rem;margin:20px 0}
        .hora {background:#ff3366;display:inline-block;padding:12px 30px;border-radius:50px;font-size:2rem;font-weight:bold}
        .zoom {margin:20px 0;font-size:1.3rem}
        .descripcion {font-size:1.8rem;margin:40px 0;line-height:1.4}
        .btn-reserva {background:#fff;color:#000;font-size:1.8rem;font-weight:bold;padding:18px 50px;border-radius:50px;text-decoration:none;display:inline-block;margin:30px 0}
    </style>

    <!-- PayPal Parte 1 -->
    <script src="https://www.paypal.com/sdk/js?client-id=BAAyhcVYLUh7ex5oqlmTe5QuQhpDB5KUKg6lnTGJmURfbO0WPUo1D6go1LdGnyWuPB5k_LJsOGqIqTiFWQ&components=hosted-buttons&disable-funding=venmo&currency=USD"></script>
</head>
<body>
    <div class="container">
        <h1>Taller <span class="de">de</span><br><span>Canva</span></h1>
        
        <div class="fecha">12/12 • Viernes</div>
        <div class="hora">7:00 PM - 9:00 PM</div>
        <div class="zoom">Vía Zoom</div>
        
        <p class="descripcion">
            Descubre cómo aprender a utilizar Canva<br>
            <strong>en tan solo 2 horas</strong>
        </p>

        <!-- PayPal Parte 2 - Botón de pago -->
        <div id="paypal-container-85SH8GX5MXYMJ"></div>
        <script>
          paypal.HostedButtons({
            hostedButtonId: "85SH8GX5MXYMJ",
          }).render("#paypal-container-85SH8GX5MXYMJ")
        </script>

        <br><br>
        <small>Después del pago serás redirigido automáticamente al formulario de registro.</small>
        
        <br><br>
        <a href="https://forms.gle/iau6VuFNnp4eXRSK7" class="btn-reserva" target="_blank">
            O REGISTRARME DIRECTO (si ya pagaste)
        </a>
    </div>
</body>
</html>
