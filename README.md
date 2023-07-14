# m2_ae7_abp_grupal_1
Repositorio para la actividad grupal 7 del módulo 2

## Instrucciones para clonar el repositorio

Para clonar un repositorio de GitHub en una computadora, sigue estos pasos:

1. Abre la página del repositorio en GitHub que deseas clonar.

2. Haz clic en el botón verde "Code" cerca de la parte superior derecha de la página. Esto abrirá un menú desplegable.

3. En el menú desplegable, asegúrate de que esté seleccionada la opción "HTTPS" si deseas clonar el repositorio utilizando HTTPS. Si prefieres utilizar SSH, selecciona la opción "SSH" en su lugar.

4. Haz clic en el ícono del portapapeles junto a la URL del repositorio para copiarla al portapapeles.

5. Abre la terminal en tu computadora.

6. Navega hasta el directorio donde deseas clonar el repositorio utilizando el comando `cd <directorio>` (por ejemplo, `cd Documents` para navegar al directorio "Documents").

7. Una vez que te encuentres en el directorio deseado, utiliza el comando `git clone` seguido de la URL del repositorio que copiaste en el portapapeles. Por ejemplo:

   ```
   git clone https://github.com/usuario/repositorio.git
   ```

   Si estás utilizando SSH, la URL será similar a `git@github.com:usuario/repositorio.git`.

8. Presiona Enter y Git comenzará a clonar el repositorio en tu computadora. Verás un mensaje que indica el progreso de la clonación y, una vez finalizado, se creará una nueva carpeta con el nombre del repositorio en el directorio actual.

Ahora has clonado exitosamente el repositorio de GitHub en tu computadora. Puedes comenzar a trabajar con los archivos del repositorio y realizar cambios localmente.

## Instrucciones para subir cambios hechos localmente

Para subir los cambios hechos localmente a un repositorio en GitHub, sigue estos pasos:

1. Abre la terminal y navega hasta el directorio raíz del repositorio en tu computadora utilizando el comando `cd <directorio>` (por ejemplo, `cd Documents/repositorio`).

2. Verifica el estado de tu repositorio local ejecutando el comando `git status`. Esto te mostrará los archivos modificados, eliminados o agregados.

3. Si deseas agregar todos los archivos modificados al área de preparación para enviarlos en el siguiente commit, utiliza el comando `git add .`. Si solo deseas agregar archivos específicos, utiliza el comando `git add <nombre_archivo>`.

4. Confirma los cambios utilizando el comando `git commit -m "Mensaje del commit"`, donde "Mensaje del commit" es una descripción breve de los cambios realizados.

5. Luego de confirmar los cambios localmente, utiliza el comando `git push origin <rama>` para enviar los cambios al repositorio remoto en GitHub. Reemplaza `<rama>` con el nombre de la rama en la que deseas enviar los cambios (por lo general, es "main" o "master").

6. Si es la primera vez que estás enviando los cambios a la rama remota, es posible que se te solicite autenticación. Ingresa tus credenciales de GitHub (nombre de usuario y contraseña o token de acceso personal) cuando se te solicite.

7. Una vez completado el comando `git push`, Git enviará los cambios al repositorio remoto en GitHub. Puedes verificar los cambios visitando el repositorio en GitHub y navegando a la rama correspondiente.

Ten en cuenta que es posible que debas resolver conflictos si hay cambios conflictivos entre el repositorio remoto y tu repositorio local. En ese caso, Git te proporcionará instrucciones sobre cómo resolver los conflictos.

Recuerda que es una buena práctica realizar un `git pull` antes de hacer un `git push` para asegurarte de tener las últimas actualizaciones del repositorio remoto en tu repositorio local.
