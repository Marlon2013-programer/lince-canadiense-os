//# lince-canadiense-os
Lince Canadiense OS es un sistema operativo de prueba para hacer pruebas para evitar errores en la programación solo es un proyecto por el momento
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Lince Canadiense OS – Simulador</title>
<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: linear-gradient(135deg, #3b3f87, #6a4bcf);
  height: 100vh;
  overflow: hidden;
}

/* Barra superior */
.topbar {
  height: 40px;
  background: rgba(0,0,0,0.4);
  color: white;
  display: flex;
  align-items: center;
  padding: 0 15px;
  justify-content: space-between;
}

/* Escritorio */
.desktop {
  position: relative;
  height: calc(100vh - 90px);
}

/* Ventana */
.window {
  width: 500px;
  background: #f4f4f4;
  border-radius: 10px;
  position: absolute;
  top: 60px;
  left: 50px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.3);
}

.window-header {
  background: #ddd;
  padding: 8px;
  border-radius: 10px 10px 0 0;
  font-weight: bold;
}

.window-content {
  padding: 15px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 15px;
}

.folder {
  text-align: center;
  cursor: pointer;
}

.folder img {
  width: 48px;
}

/* Dock */
.dock {
  height: 50px;
  background: rgba(0,0,0,0.5);
  position: absolute;
  bottom: 0;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}

.dock img {
  width: 32px;
  cursor: pointer;
}
</style>
</head>
<body>

<div class="topbar">
  <div>🦁 Lince Canadiense OS</div>
  <div>📶 75% 🔋 10:22</div>
</div>

<div class="desktop">

  <div class="window">
    <div class="window-header">Explorador de Archivos</div>
    <div class="window-content">
      <div class="folder">
        📁
        <div>Documentos</div>
      </div>
      <div class="folder">
        📁
        <div>Imágenes</div>
      </div>
      <div class="folder">
        📁
        <div>Videos</div>
      </div>
      <div class="folder">
        📁
        <div>Proyectos</div>
      </div>
      <div class="folder">
        📁
        <div>Música</div>
      </div>
      <div class="folder">
        📁
        <div>Trabajo</div>
      </div>
    </div>
  </div>

</div>

<div class="dock">
  🗂️ 🌐 ⚙️ 📝 🎵
</div>

</body>
</html>
