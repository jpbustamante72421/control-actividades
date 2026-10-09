1. Flujo colaborativo

Supón que quieres colaborar con el repositorio de otro desarrollador. 
Ordena y explica los siguientes elementos:
Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y 
Modificar archivos. Agrega cualquier operación que consideres 
necesaria.

Fork: Creara una copia del repositorio original en tu cuenta que 
seleccionaste de GitHub.

Clone: Descargar el repositorio en tu computadora para trabajar en 
el desde tu computadora sin perjudicar el repositorio original.

Branch: Esto creara una rama nueva donde se realizaran los cambios 
sin modificar la rama principal.

Modificar archivos: Se realizan los cambios necesarios que se requieran en el proyecyo o codigo en la documentación o archivos del mismo proyecto.

Commit: Este lo que hace es guardar los cambios realizados en el repositorio local con un mensaje que describa lo que se hizo.

Push: Subir los cambios de tu rama local a tu repositorio remoto en 
GitHub.

Pull Request: Envia una solicitud al propietario o jefe del 
repositorio original para que revise, apruebe o rechace tus cambios.

Review: El propietario o el jefe revisa los cambios para verificar que sean correctos y en caso de que no se mandaran a modificar.

Merge: Ya que se hayan aprobados los cambios se integran a la rama 
principal del repositorio original.

2. Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es 
correcta
y explica la diferencia entre Fork y Clone.

SÍ es correcto ya que el Fork llega a crear una copia de un repositorio dentro de tu cuenta seleccionada 
en la nube de GitHub y el Clone descarga los archivos de un repositorio directamente a tu computadora.

3. Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman 
parte del repositorio original? ¿Qué debe ocurrir para incorporarlos?

NOO los cambios aún no forman parte del repositorio original ya que al hacer push los cambios solo se 
subieron a tu copia del repositorio que hiciste Fork y clone.

Para incorporarlos se tiene que crear un pull equest desde la rama de tu fork hacia la rama 
correspondiente del repositorio original, que te revisen el código y una vez aprobado finalmente forma 
parte del proyecto principal.

4. Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si 
necesitas crear otro Pull Request y qué ocurre cuando realizas nuevamente push.

No se necesita crear otro pull request ya que los cambios que fueron regresados antes de ser aceptados 
siguen formando parte del mismo pull request, y a la hora de hacer el push, automaticamente aparece
la opción de aceptar o no los cambios.

5. Merge y repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del 
propietario no contiene los cambios. Explica por qué sucede y qué operación debe realizarse.

Esto sucede ya que el repositorio local y el de la nube son independientes, a la hora de que se hace el 
Merge no aparecera por lo mismo que son independientes, para esto se tendra que hacer un git pull en el 
la terminal del proyecto original y asi poder ver los cambios en el repositorio local y en la nube.

6. Sync Fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué 
herramienta utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.

Se utilizaría la opción sync fork para actualizar mi fork con los cambios recientes del 
repositorio original y se actualiza mi fork en GitHub ya incorporando los nuevos commits del repositorio 
original sin modificarlo.

El sync fork actualiza el fork en GitHub con los cambios del repositorio original mientras que
el git pull descarga e integra los cambios de un repositorio remoto en mi repositorio local.
