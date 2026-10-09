 Pasos para colaborar 

Ordena y explica los pasos necesarios para colaborar con el repositorio de otro desarrollador utilizando Fork, Clone, Branch, Commit, Push, Pull Request, Review, Request Changes y Merge.

Mi respuesta

1. Fork: Entro al repositorio de mi compañero en GitHub y presiono Fork para crear una copia en mi cuenta.
2. Clone:Copio la URL de mi Fork y lo clono en Visual Studio Code para tener el proyecto en mi computadora.
3. Branch: Creo una rama nueva para realizar mis cambios sin afectar la rama principal.
4. Modificar archivos:** Abro el proyecto, realizo las modificaciones necesarias y guardo los archivos.
5. Commit: Ejecuto git add . para preparar los cambios y después git commit -m "Realicé modificaciones"` para guardarlos en el historial.
6. Push: Ejecuto git push -u origin nombre-de-mi-rama para subir mis cambios a mi repositorio de GitHub.
7. Pull Request: Entro a GitHub y creo un Pull Request para solicitar que mi compañero revise e integre mis cambios al repositorio original.
8. Review: Mi compañero revisa los cambios que realicé para verificar que el código funcione correctamente.
9. Request Changes:Si mi compañero encuentra algún error, me solicita corregirlo. Realizo las modificaciones, hago otro commit y subo los cambios con push.
10. Merge: Cuando mi compañero aprueba los cambios, los integra al repositorio original mediante Merge.


Explicación:

Este proceso me permite trabajar en una copia del proyecto, realizar modificaciones sin afectar directamente el repositorio original y proponer mis cambios para que el propietario los revise y decida si los integra.

---

2. Fork y Clone



Analiza la afirmación: «Clone crea una copia del proyecto dentro de mi cuenta de GitHub». Indica si es correcta y explica la diferencia entre Fork y Clone.

Mi respuesta:

La afirmación es incorrecta, porque Clone descarga una copia del proyecto a mi computadora, mientras que Fork crea una copia del repositorio dentro de mi cuenta de GitHub.

Explicación:

Fork se utiliza para crear una copia remota del repositorio en mi cuenta de GitHub. Clone se utiliza para descargar el repositorio a mi computadora y trabajar en él desde Visual Studio Code.



3. Pull Request

Planteamiento o pregunta:

Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. ¿Los cambios ya forman parte del repositorio original? ¿Qué debe ocurrir para incorporarlos?

Mi respuesta:

No, los cambios todavía no forman parte del repositorio original. Para incorporarlos, debo crear un Pull Request para que el propietario revise los cambios y, si los aprueba, realice el Merge.

Explicación:

Push solamente sube mis cambios a mi Fork. El Pull Request permite proponerlos al repositorio original, y el Merge los integra cuando se autoriza su incorporación.



4. Request Changes


El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear otro Pull Request y qué ocurre cuando realizas nuevamente push.

Mi respuesta:

Debo revisar los comentarios del propietario, corregir los errores y guardar los cambios con un nuevo commit. Después, realizo nuevamente push a la misma rama. No necesito crear otro Pull Request, porque el que ya existe se actualiza automáticamente.

Explicación:

Request Changes indica que se necesitan correcciones. Al subir los nuevos commits a la misma rama, estos aparecen en el Pull Request existente para que el propietario vuelva a revisar los cambios.



5. Merge y repositorio local



Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no contiene los cambios. Explica por qué sucede y qué operación debe realizarse.

Mi respuesta:

Esto sucede porque el Merge se realizó en GitHub, pero los cambios todavía no se han descargado al repositorio local del propietario. Para actualizarlos, debe ejecutar git pull origin main desde su repositorio local, estando en la rama main.

Explicación:

El Merge integra los cambios en el repositorio remoto, pero no actualiza automáticamente las copias locales. Con git pull origin main el propietario descarga e integra los cambios de la rama remota main en su rama local.

 

7. Registrar el cambio en un cuarto commit y subirlo a GitHub


Registra este cambio en un cuarto commit con un mensaje descriptivo y súbelo a GitHub.
*Mi respuesta:

Primero guardaría los cambios en los archivos. Después, abriría la terminal de Visual Studio Code y ejecutaría los siguientes comandos:

bash
git add .
git commit -m "Actualiza respuestas de colaboracion con GitHub"
git push origin main


Así guardaría los cambios en un cuarto commit y los subiría a GitHub. Si estoy trabajando en otra rama, debo sustituir main por el nombre de esa rama.

Explicación:

Con git add . preparo los archivos modificados, con git commit registro los cambios en el historial local y con git push envío los commits al repositorio remoto.

Para comprobar que sea mi cuarto commit, puedo ejecutar git log --oneline y revisar el historial de la rama actual.
