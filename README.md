# proyecto-mercado
git clone https://github.com/xiomara/proyecto-mercado.git
Proyecto académico para la creación de un marketplace de productos artesanales.  
Se utiliza **Git y GitHub** para la gestión de ramas, commits y pull requests.


# Estar en main y crear rama
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
 mercado  Artesanal
</head>
<body>
  <h1>Marketplace de Productos Artesanales</h1>

  <h2>Productos</h2>
  <ul>
    <li>Sombrero de paja toquilla - $25</li>
    <li>Bolso tejido a mano - $30</li>
    <li>Jarro de cerámica pintado - $15</li>
  </ul>
</body>
</html>


# ( lista de productos)
<head>
  <meta charset="UTF-8">
  mercado artesanal 
   <ul>
    <li>Sombrero de paja toquilla  </li>
    <li>Bolso tejido a mano </li>
    <li>Jarro de cerámica pintado </li>
    <li>ropa tejida a mano </li>
    <li>faldas con pintado a mano  </li>
  </ul>
  
  <link rel="stylesheet" href="styles.css">
</head>





# ( diseño)
body {
  font-family: Arial, sans-serif;
  margin: 20px;
  background-color: #f9f9f9;
}

h1 {
  text-align: center;
  color: #4CAF50;
}

ul {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
  list-style: none;
  padding: 0;
}

li {
  background: white;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 8px;
  text-align: center;
}

# ( formulario de contacto)
<h2>Contacto</h2>
<form>
  <label for="nombre">Nombre:</label><br>
  <input type="text" id="nombre" name="nombre"><br><br>

  <label for="correo">Correo:</label><br>
  <input type="email" id="correo" name="correo"><br><br>

  <label for="mensaje">Mensaje:</label><br>
  <textarea id="mensaje" name="mensaje"></textarea><br><br>

  <button type="submit">Enviar</button>
</form>

# ( footer en style.css)
<footer>
  <p>© 2025 Marketplace Artesanal</p>
</footer>


footer {
  margin-top: 20px;
  text-align: center;
  background: #4CAF50;
  color: white;
  padding: 10px;
  border-radius: 8px;
}

@media (max-width: 600px) {
  footer p {
    font-size: 14px;
    text-align: center;
  }
}


