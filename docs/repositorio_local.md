🧩 ¿Qué es un repositorio local?

Un repositorio local es una carpeta en tu computadora donde Git comienza a rastrear los cambios de los archivos de un proyecto (versionado).

🛠️ Pasos para crear un repositorio local con Git
1️⃣ Abrir la terminal

Ubícate en la carpeta donde quieres crear tu proyecto usando la consola:

cd ruta/del/proyecto

2️⃣ Inicializar el repositorio

Dentro de la carpeta del proyecto, ejecuta:

git init


📌 Este comando:

Crea una carpeta oculta llamada .git

Convierte la carpeta en un repositorio Git

3️⃣ Ver el estado del repositorio

Para comprobar que Git está funcionando:

git status


Verás que no hay commits y que Git detecta los archivos sin seguimiento.

4️⃣ Agregar archivos al área de preparación (staging)

Para agregar todos los archivos:

git add .


O un archivo específico:

git add archivo.txt

5️⃣ Crear el primer commit

Guarda el estado inicial del proyecto con un commit:

git commit -m "Primer commit"


📌 El commit crea un punto de guardado del proyecto.