# hi-people👋
**`hi-people`** es un repositorio con propósito educativo para aprender a utilizar GitHub. El objetivo de este proyecto es recopilar el nombre/alias, usuario en GitHub y perfil en LinkedIn de los miembros del DAMDAWTeam.

## ¿Cómo contribuir?
**IMPORTANTE:** Antes de empezar con estos pasos, debes crear una cuenta en GitHub y pasar tu nombre de usuario por el [grupo de Telegram](https://t.me/daw_dam_cidead). Así podremos invitarte a formar parte de DAMDAWTeam y otorgarte permisos para realizar cambios sobre el repositorio 😉

1. Descarga e instala `git` en tu equipo la [versión para tu sistema operativo](https://git-scm.com/downloads).

2. Abre la terminal y dirígete al directorio donde vayas a trabajar (en Windows abrir Git Bash haciendo click derecho sobre cualquier parte de la carpeta y escoger la opción *Git Bash here*). No cierres la terminal, que solo acabamos de empezar con ella 😜

3. Una vez ubicados en el directorio con nuestra terminal, clonaremos este repositorio al mismo con el siguiente comando `git clone https://github.com/DAMDAWTeam/hi-people.git`. Si todo ha ido bien verás una nueva carpeta en tu directorio con los archivos del repositorio.

4. Entra en el directorio y modifica el archivo [`people.md`](people.md) con un editor de texto plano (bloc de notas, NotePad++, etc), añadiendo tu Nombre/Alias, usuario en GitHub y enlace a tu perfil de LinkedIn. guárdalo y vamos al siguiente paso.

5. Vamos a ver lo que ha pasado en el repositorio. Para ello, vuelve a tu terminal (la misma que usaste para hacer el `clone`) e introduce el comando `cd hi-people` para acceder al directorio del repositorio. Una vez dentro ejecuta `git status`. Este comando nos devolverá el estado de nuestro repositorio local (rama/branch en la que nos encontramos trabajando y qué archivos han sido modificados en rojo). Si queremos más detalles sobre los cambios realizados en un archivo podemos ejecutar `git diff people.md`.

6. Ahora vas a crear tu rama para poder añadir los cambios a ella sin trastocar la rama principal. Para ello ejecuta el siguiente comando `git checkout -b tunombre-add`. Con esto acabamos de crear una nueva rama llamada `tunombre-add` dentro del repositorio donde vamos a añadir los cambios que has realizado. Para comprobar que te encuentras en otra rama puedes ejecutar `git status`, de hecho, es una buena práctica ejecutarlo de vez en cuando para no perder de vista el estado de nuestro repositorio.

7. Una vez creada la rama vamos a añadir los cambios realizados y comentarlos. Para ello ejecuta `git add .` para añadir el fichero, y en una nueva línea `git commit -m "Añadido Mi Nombre"` para comentar los cambios realizados (El comentario entre comillas debe ser lo más descriptivo posible sobre los cambios realizados).

9. Ya estamos casi terminando. Ahora subiremos nuestra rama al repositorio en GitHub. Para ello ejecutaremos el comando `git push origin tunombre-add`. Fíjate que donde `tunombre-add` corresponde con el nombre de la rama que creaste en el paso 6, por lo que tendrás que modificarlo para que sea igual. Si es la primera vez que usas GitHub desde la terminal te pedirá introducir tus datos de acceso (usuario y contraseña). Si todo ha ido bien se cargará un mensaje en la terminal con información de los cambios, ya lo tenemos casi ¡No cierres la terminal! Solo nos queda un paso con ella.

10. Fíjate bien en el mensaje que nos ha devuelto la terminal. Entre las líneas deberías ver algo como esto:
    ```
    Create a pull request for 'readme-fixed' on GitHub by visiting: https://...
    ```
    Lo que tendrás que hacer es pulsar la tecla `Ctrl + Click` sobre el enlace para poder crear directamente un Pull Request desde la página de GitHub. Con esto estaremos creando una solicitud para que los cambios en nuestra rama sean incluidos en la rama principal.
    
11. Dale al botón gordo que pone "Create Pull Request" y... ¡ya está! Los cambios que has realizado aún no se verán en la rama principal del repositorio hasta que alguien revise los cambios que has realizado sobre el proyecto. Cuando esto ocurra recibirás una notificación informándote de si tu Pull Request ha sido aceptada (si está todo bien) o rechazada (si hay alguna cosa que mejorar).
