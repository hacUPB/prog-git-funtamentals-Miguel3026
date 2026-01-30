## Proceso para crear repositorio remoto
Para crear un repositorio remoto en GitHub y sincronizarlo con un repositorio local, primero se debe ingresar a la cuenta de GitHub desde el navegador web. Una vez dentro, se hace clic en el botón New repository, se asigna un nombre al repositorio, se elige si será público o privado y se crea el repositorio sin añadir archivos iniciales. Al finalizar, GitHub muestra la dirección del repositorio remoto, que se usará para enlazarlo con el repositorio local.

Luego, en la consola, se accede a la carpeta del proyecto que ya tiene un repositorio local creado con Git. Para conectar el repositorio local con el repositorio remoto, se utiliza el comando **git remote add origin URL_DEL_REPOSITORIO**, donde la URL corresponde a la proporcionada por GitHub. Después, se envían los archivos del repositorio local al repositorio remoto usando el comando **git push -u origin main** . Con este proceso, ambos repositorios quedan sincronizados y los cambios realizados localmente pueden guardarse y compartirse en GitHub.

Hay que tener en cuenta que si en git aparece la rama de (master) debemos cambiarla a main con el siguiente comando **git branch -m master main**

