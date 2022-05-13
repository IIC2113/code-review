# Ayudantía de Code Review (PR)

Este repositorio tiene como objetivo que puedas practicar cómo hacer Pull Requests.

### Instrucciones

Recuerda utilizar lo aprendido en cuanto a *branches* para crear tu propio espacio de trabajo, modificar y agregar los archivos pedidos y subir tu Pull Request para que sea revisada. Estos son los archivos que tu PR deberá modificar:

* Agrega un archivo `*.html` a la carpeta `people/` con tu usuario de GitHub. Por ejemplo, mi usuario es **igbasly**, así que mi archivo se llamará... `igbasly.html`. Puedes ver los que ya existen en la carpeta e inspirarte en esos.
* Agrega tu usuario en el archivo `people.txt`. Por favor intenta respetar el **orden alfabético** al agregarlo (de la A la Z, ignoremos si es mayúscula o no).
* Agrega en el archivo `index.html` un nuevo `div` como el siguiente y cambia el id por tu usuario de github.
    ```html
    <div class="border rounded-md w-36 p-2 h-36" id="usuario_github">
        Informaciona a agregar...
    </div> 
    ```
* Puede que al momento de subir tu Pull Request, te indique que existen conflictos que deben ser resueltos en el archivo `people.txt`, ya que es un archivo que está siendo modificado por muches ayudantes al mismo tiempo. Debes seleccionar la opción de _Resolve conflicts_ y editar el archivo para resolver el conflicto, asegurandote de que **todos los nombres de usuario presentes** se mantengan en el archivo final.
