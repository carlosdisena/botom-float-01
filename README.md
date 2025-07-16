<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Botón WhatsApp Flotante</title>
  <style>
    body { margin: 0; height: 200vh; }
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      z-index: 1000;
      animation: float 2s ease-in-out infinite;
    }
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-5px); }
      100% { transform: translateY(0px); }
    }
  </style>
</head>
<body>
  <a href="https://wa.me/573028476182?text=🛒%20Hola,%20deseo%20realizar%20el%20siguiente%20pedido%20con%20los%20siguientes%20productos.%0A📦%20Productos:%0A👤%20Nombre:%0A🏡%20Dirección:%0A📍%20Barrio/Zona:"
     class="whatsapp-float" target="_blank" rel="noopener">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png"
         alt="WhatsApp" width="60" height="60">
  </a>
</body>
</html>
