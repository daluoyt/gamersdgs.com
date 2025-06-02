# gamersdgs.com
<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GamersDGS - Generador Free Fire</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🎮 GamersDGS - Generador Free Fire</h1>
    <nav>
      <a href="https://youtube.com/@daluo_yt?si=cEvFO_L5YXV6I-dq" target="_blank">YouTube</a>
      <a href="https://www.instagram.com/daluo_yt/profilecard/?igsh=cHM0MmY1MDZxMGo4" target="_blank">Instagram</a>
    </nav>
  </header>  <main>
    <section id="simulador">
      <h2>Simulador de Diamantes</h2>
      <input type="text" placeholder="Ingresa tu ID de jugador" id="playerId">
      <label>Selecciona cantidad de diamantes:</label>
      <select id="diamantes">
        <option>100</option>
        <option>500</option>
        <option>1000</option>
        <option>5000</option>
      </select>
      <label>Elige una skin:</label>
      <select id="skins">
        <option>Hip Hop</option>
        <option>Cr7 Chrono</option>
        <option>Hayato Llama Azul</option>
        <option>Wukong Camuflaje</option>
      </select>
      <button onclick="procesar()">Generar</button>
    </section><section id="juego">
  <h2>🎁 Caja Misteriosa</h2>
  <button onclick="abrirCaja()">Abrir Caja</button>
  <p id="recompensa"></p>
</section>

<section id="noticias">
  <h2>📰 Trucos y Noticias</h2>
  <ul>
    <li>🔥 Cómo conseguir diamantes sin pagar (2025)</li>
    <li>⚔️ Mejores armas evolutivas para clasificatoria</li>
    <li>🕶️ Trucos secretos para subir de rango rápido</li>
  </ul>
</section>

  </main>  <footer>
    <p>&copy; 2025 GamersDGS | Página fan no oficial de Free Fire</p>
  </footer>  <script>
    function procesar() {
      const id = document.getElementById('playerId').value;
      if (!id) {
        alert("Por favor ingresa tu ID de jugador.");
        return;
      }
      alert("Procesando solicitud para el ID: " + id + "...\n⚙️ Generando diamantes y skins...");
    }

    function abrirCaja() {
      const premios = ["500 diamantes", "Skin rara", "Emote exclusivo", "Caja vacía 😢"];
      const premio = premios[Math.floor(Math.random() * premios.length)];
      document.getElementById("recompensa").innerText = "🎉 Has recibido: " + premio;
    }
  </script></body>
</html>
