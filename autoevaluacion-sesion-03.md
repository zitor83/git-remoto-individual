# Autoevaluación Sesión 03

**1. ¿Qué diferencia hay entre Git y GitHub?**
Git es el software de control de versiones para trabajar en local. GitHub es una plataforma que aloja repositorios Git en la nube. 

**2. ¿Qué diferencia hay entre repositorio local y repositorio remoto?**
El local reside en el disco duro de mi ordenado. El remoto está en un servidor (como GitHub) y actúa como centro para compartir código.

**3. ¿Qué has hecho hoy para conectar ambos?**
He utilizado el comando `git remote add origin <URL>` para enlazar mi carpeta local con la dirección del repositorio vacío en GitHub.

**4. ¿Qué diferencia hay entre git fetch, git pull y git push?**
* **fetch:** Descarga la información del remoto para ver qué cambios hay nuevos, pero no modifica mis archivos locales.
* **pull:** Descarga los cambios del remoto y los fusiona inmediatamente en mi rama actual local.
* **push:** Sube mis commits locales para publicarlos en el repositorio remoto.

**5. ¿Por qué no conviene trabajar directamente sobre la rama principal?**
Para proteger el código estable o en producción. Trabajar en ramas paralelas permite aislar funcionalidades, hacer pruebas y revisar el código antes de integrarlo.

**6. ¿Qué representa una Pull Request?**
Es una propuesta formal de integración y un espacio de comunicación. Sirve para pedir al equipo que revise el trabajo de una rama antes de fusionarlo con la principal.

**7. ¿Qué paso de la sesión te ha ayudado más a entender Git remoto?**
Hacer el primer `git push` y comprobar visualmente que aparecia todo.

**8. ¿Qué aspecto te sigue resultando menos intuitivo?**
Las Pulls Request
