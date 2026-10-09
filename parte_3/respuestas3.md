1. Analiza


Explica qué ocurre en cada instrucción:

bash
git status
git add README.md
git commit -m "Actualiza documentación"
git push


Mi respuesta:

* git status: muestra el estado de los archivos del proyecto.
* git add README.md: prepara el archivo README.md para guardar sus cambios.
* git commit -m "Actualiza documentación"`: guarda los cambios preparados en el historial local de Git.
* git push: sube los commits al repositorio remoto de GitHub.

Explicación:

Primero reviso el estado de mis archivos, después preparo el archivo que modifiqué, guardo los cambios en un commit y finalmente los envío a GitHub para actualizar el repositorio remoto.



2. Identifica qué falta

Caso A



Modificar archivo → git add  → ¿? → git push

Mi respuesta:

La operación que falta es git commit.

Explicación:

Después de preparar los archivos con git add ., debo ejecutar git commit para registrar los cambios en el historial local antes de subirlos a GitHub con git push.

Caso B



Repositorio GitHub → ¿? → Repositorio local

respuesta:

Utilizaría el comando git clone.

Explicación:

Este comando descarga una copia del repositorio de GitHub a mi computadora, incluyendo los archivos y el historial de Git, para poder trabajar en el proyecto localmente.

 Caso C


Repositorio remoto actualizado → ¿? → Repositorio local actualizado

Mi respuesta:

Utilizaría el comando git pull.

Explicación:

Este comando descarga e integra los cambios del repositorio remoto en mi repositorio local para mantenerlo actualizado con los últimos cambios disponibles.

 3. Registrar el cambio en un quinto commit y subirlo a GitHub



Registrar este cambio en un quinto commit con un mensaje descriptivo y subirlo a GitHub.

Mi respuesta:

Ejecutaría los siguientes comandos en la terminal de Visual Studio Code:

bash
git status
git add .
git commit -m "Agrega analisis de comandos Git"
git push

Explicación:

Primero reviso el estado de los archivos, después preparo los cambios, creo un commit con un mensaje descriptivo y finalmente subo los cambios a GitHub. Para comprobar que sea mi quinto commit, puedo revisar el historial con git log --oneline
