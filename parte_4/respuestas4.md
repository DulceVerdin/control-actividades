 Parte 4. Conceptos

1. Explica la diferencia entre Git y GitHub.



Explica la diferencia entre Git y GitHub.

Mi respuesta:

Git es un sistema de control de versiones que utilizo en mi computadora para registrar los cambios de un proyecto. GitHub es una plataforma en internet donde puedo almacenar repositorios y colaborar con otras personas.

Explicación:

Git me permite controlar el historial de mi código localmente, mientras que GitHub me permite compartirlo y trabajar en equipo desde internet.


2. Explica para qué sirve .gitignore


Explica para qué sirve.gitignore

Mi respuesta:

El archivo .gitignore sirve para indicar a Git qué archivos o carpetas no quiero incluir en el seguimiento del repositorio, como archivos temporales, la carpeta __pycache__ o el entorno virtual `.venv`.

explicación:

Me ayuda a mantener el repositorio organizado y evita que se incluyan archivos innecesarios al compartir el proyecto en GitHub.



3. Explica por qué .venv no debe almacenarse normalmente en GitHub.

**Planteamiento o pregunta:**

Explica por qué .venv no debe almacenarse normalmente en GitHub.

Mi respuesta:

La carpeta .venv no se suele subir a GitHub porque contiene las librerías instaladas para mi proyecto, ocupa espacio y puede variar dependiendo de la computadora. Es mejor compartir el archivo `requirements.txt para instalar las dependencias en cada computadora.

Explicación:

Cada persona puede crear su propio entorno virtual e instalar las librerías necesarias, evitando subir muchos archivos que pueden generarse nuevamente.



4. Explica para qué sirve requirements.txt

**Planteamiento o pregunta:**

Explica para qué sirve requirements.txt

**Mi respuesta:**

El archivo requirements.txt sirve para registrar las librerías y sus versiones que necesita mi proyecto de Python. Para instalarlas utilizo el comando pip install -r requirements.txt

Explicación:

Este archivo facilita compartir el proyecto con otras personas, porque les permite instalar las dependencias necesarias sin tener que buscarlas una por una.

5. Explica la diferencia entre Stage, Commit y Push.


Explica la diferencia entre Stage, Commit y Push.

Mi respuesta:

* Stage: preparo los archivos modificados que quiero incluir en el siguiente registro.
* Commit: guardo los cambios preparados en el historial local de Git.
* Push: envío los commits de mi repositorio local al repositorio remoto de GitHub.

Explicación:

Estas operaciones se utilizan en diferentes etapas. Primero selecciono los cambios, después los registro en mi historial local y finalmente los envío a GitHub para compartirlos.

6. Explica por qué un repositorio puede tener varios commits antes de realizar un push.


Explica por qué un repositorio puede tener varios commits antes de realizar un push.

Mi respuesta

Un repositorio puede tener varios commits antes de realizar un push porque cada commit guarda un avance en el historial local. Puedo hacer varios commits mientras trabajo y después subirlos juntos a GitHub.

Explicación:

Los commits se guardan localmente y no necesitan enviarse inmediatamente a GitHub. Cuando realizo un push, puedo enviar varios commits pendientes en una sola operación.
