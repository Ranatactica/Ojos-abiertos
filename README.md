# Ojos-abiertos
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ojos Abiertos</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>OJOS ABIERTOS</h1>
    <p>Tu voz importa. Este es un espacio seguro para denunciar y transformar tu entorno.</p>
    
    <form id="denuncia-form">
      <label for="categoria">Categoría</label>
      <select id="categoria" required>
        <option value="">Selecciona una categoría</option>
        <option value="soborno">Soborno</option>
        <option value="contratos">Contratación irregular</option>
        <option value="abuso">Abuso de poder</option>
      </select>

      <label for="descripcion">Descripción</label>
      <textarea id="descripcion" required placeholder="Describe lo sucedido..."></textarea>

      <label for="imagen">Adjuntar imagen (opcional)</label>
      <input type="file" id="imagen">

      <button type="submit">Enviar denuncia</button>
    </form>
  </div>

  <script src="app.js"></script>
</body>
</html>
