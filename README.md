#🐍 01 - Django Project

Proyecto base de Django — guía rápida de instalación y configuración

Autora: Camila Morales

📑 Tabla de contenidos
📦 Clonar el repositorio
⚙️ Configuración de Git
🚀 Puesta en marcha
📁 Estructura del proyecto
🤝 Contribuciones
📦 Clonar el repositorio

Para obtener una copia local del proyecto, ejecuta:

bash
git clone <url-del-repositorio>

💡 Tip: reemplaza <url-del-repositorio> por la URL real que copiaste desde GitHub (botón verde Code).

⚙️ Configuración de Git

Antes de empezar a trabajar, verifica y configura tu identidad de Git.

1️⃣ Inspeccionar configuración actual
bash
git config --global --list

Este comando muestra el nombre de usuario y correo actualmente configurados en tu cuenta de Git.

2️⃣ Configurar nombre de usuario
bash
git config --global user.name "nombre_usuario"
3️⃣ Configurar correo electrónico
bash
git config --global user.email "correo_electronico"
<details> <summary>❓ ¿Por qué es importante este paso?</summary> <br>

Git asocia cada commit con un nombre y un correo. Si no los configuras, tus commits podrían quedar registrados con datos genéricos o incorrectos, dificultando el seguimiento de cambios en equipo.