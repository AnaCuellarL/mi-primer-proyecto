# ¿Cómo crear un repositorio remoto con Git Hub?

El día de hoy realizamos un repositorio en GitHub, para ello lo primero que hacemos es ingresar a Git Hub y registrarnos, posteriormente debemos dar click al botón "+" y al botón "new repository", al momento de dar click en ese botón se rediccionará a una especie de formulario, se agrega el nombre del repositorio y una breve descripción y se crea el repositorio, en el caso de hoy no vamos a crear un archivo README desde cero sino que lo vamos a importar desde un repositorio local, para ello debemos ingresar al repositorio ya previamente hecho y agregar el enlace que aparece en la sección **OR push an existing repository from command line**  y para verificar que si funciono escribimos la linea de código:

- git remote -v

Después de ingresado este código debe salir dos veces el enlace anteriormente copiado dos veces (uno con la palabra fetch y el otro con la palabra push entre parentesis)

Despues de esto se debe escribir el código **git push -u origin main** despues de esto se abre una ventana emergente que pide un registro, se ingresa y se da click en ingresar.

Una vez ingresado aparece en Gitbash ya enlazado, finalmente, ya esta subido el repositorio a Git Hub.
¡[texto](Captura.jpg)
