# proyecto-mercado
git clone https://github.com/xiomara/proyecto-mercado.git
cd proyecto-mercado

# Estar en main y crear rama
git checkout -b feature/productos

# (aquí editas app.js para añadir lista de productos)
git add .
git commit -m "feat(productos): agregar lista inicial de productos"

# Subir rama a GitHub
git push -u origin feature/productos

git checkout main
git pull origin main
git checkout -b feature/estilos

# (aquí editas style.css para mejorar el diseño)
git add .
git commit -m "feat(estilos): mejorar diseño responsivo"

git push -u origin feature/estilos

git checkout main
git pull origin main
git checkout -b feature/contacto

# (aquí editas index.html para agregar formulario de contacto)
git add .
git commit -m "feat(contacto): agregar formulario de contacto"

git push -u origin feature/contacto

git checkout main
git pull origin main
git checkout -b fix/estilos-footer

# (aquí corriges el footer en style.css)
git add .
git commit -m "fix(footer): corregir alineación en pantallas pequeñas"

git push -u origin fix/estilos-footer

