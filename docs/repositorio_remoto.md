🌐 ¿Qué es un repositorio remoto?

Un repositorio remoto es una copia del proyecto alojada en Internet (por ejemplo, en GitHub).
Sirve para:

Guardar el proyecto en la nube

Compartir código

Trabajar en equipo

Tener respaldo del trabajo

🧩 Paso 1: Crear el repositorio remoto en GitHub

Entra a GitHub e inicia sesión.

Haz clic en “New repository”.

Completa los datos:

Repository name: nombre del proyecto

Description (opcional)

Selecciona Public o Private

⚠️ No marques:

“Add a README”

“Add .gitignore”

“Choose a license”
(esto evita conflictos con el repositorio local)

Haz clic en Create repository.

GitHub te mostrará la URL del repositorio, por ejemplo:

https://github.com/usuario/proyecto.git

💻 Paso 2: Verificar el repositorio local

En tu computadora:

cd carpeta_del_proyecto
git status


Asegúrate de que:

El repositorio ya esté inicializado (git init)

Tengas al menos un commit hecho

🔗 Paso 3: Conectar el repositorio local con GitHub

Agrega el repositorio remoto con el nombre origin:

git remote add origin https://github.com/usuario/proyecto.git


Verifica la conexión:

git remote -v

⬆️ Paso 4: Subir el proyecto a GitHub (push)

Envía los commits locales al repositorio remoto:

git branch -M main
git push -u origin main


📌 Esto:

Sube el código a GitHub

Vincula la rama local main con la remota