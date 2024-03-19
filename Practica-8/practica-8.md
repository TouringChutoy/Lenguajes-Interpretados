- a. ¿Cómo se inicializa un repositorio en Git?
    - Para iniciar un repositorio en Git lo primero que se debe hacer es vincular tu cuenta de Github con Git, una vez hecho eso lo unico que se debe de hacer es utilizar el comando **git init**.

- b. ¿Cómo creas un repositorio en GitHub?
    - Una vez creado tu repositorio en Git lo que tienes que hacer es ir a Github, iniciar tu sesión y darle en **New Repository**, una vez ahi te pedira que le pongas un nombre al repositorio, podras agregar una descripción si lo deseas, si el repositorio sera publico o privado, si deseas agregar un _**README**_, si deseas agregar un **git ignore** y si deseas agregar una licencia. 

- c. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
    - Para vincular tu repositorio de Git con el repositorio de GitHub en remoto debes de usar el siguiente comando _**git remote add origin Link de tu repositorio de GitHub**_

- d. ¿Cuál es el flujo básico de trabajo en Git y GitHub?
    - Primero esta el directorio de trabajo que es donde principalmente trabajas todos los codigos o editas todas las cosas que necesite tu codigo.
    - Despues de terminar de trabajar debes hacer un **git add** para agregar todos los cambios que hayas hecho al stage y que todos los cambios esten traqueados por el repositorio.
    - Despues de eso lo que debes hacer es un _commit_ esto lo que hace es que a los cambios que hayas agregado al stage tengan una forma de identificarlos, en el _commit_ se debe agregar un mensaje que con el que se pueda identificar facilmente lo que se trabajo en esos cambios que se agregaron. El commit se hace con el siguiente comando **git commit -m "mensaje descriptivo del cambio"**
    - Por ultimo se hace un **git push**, esto lo que hace es mandar todos los cambios que estan en el stage traqueados hacia GitHub al repositorio remoto, al igual que sube el commit que hiciste para poder saber que fue lo que se hizo en esos cambios.
    - Una ultima cosa es que si estas trabajando en equipo y quieres bajar los cambios que se hayan subido al repositorio remoto por otras personas lo unico que se debe de hacer es hacer un **git pull**, de esa forma todos los cambios que no tengas tu en tu directorio de trabajo seran descargados de forma automatica y aplicados a tu directorio.

- e. ¿Para qué sirve el archivo .gitignore?
    - Sirve para hacer que a la hora de agregar cambios al stage este no pueda traquear los archivos de cierto formato o solamente un archivo, sirve principalmente si no quieres subir los archivos de cualquier formato esto lo que hace es que el **git add** ignore por completo estos archivos y no los traquee.

- f. ¿Cuál es el propósito de una rama?
    - Las ramas principalmente sirven para que se pueda trabajar en paralelo de la rama main, osea sin afectar por completo a la rama main, ya que si algo se rompe y no funciona en alguna rama siempre se puede volver a la rama main y esta puede seguir funcionando sin ningun problema mientras la otra rama se esta trabajando para que funcione correctamente y al final se pueda hacer la fusión de estas ramas. Para crear una rama se ocupa el siguiente comando **git branch nombre-rama**.

- g. ¿Qué es una fusión?
    - La fusión lo que hace es juntar dos ramas en una sola, por ejemplo esta la rama main y la rama js, si se esta trabajando con codigo en la rama js el cual se esta probando y se comprueba que los cambios de esta rama no afectan o no rompen alguna otra cosa de los archivos de la rama main se hace la fusión para juntar estas dos ramas y asi poder hacer que solamente sea una rama otra vez y que sea funcional y se pueda subir perfectamente al repositorio remoto para su uso.

- h. Explica los diferentes tipos de fusión que existen.
    - El primer tipo de fusión es la _**Fast-Forward**_, en esta fusión lo que hace es fusionar las ramas de forma automatica sin que haya algun error de por medio.
    - El segundo tipo de fusión es la _**Manual-Merge**_, Como dice su nombre la fusión se tiene que hacer de forma manual ya que existe algun problema en los archivos de las ramas como por ejemplo que algun elemento o algun texto este duplicado, o que se haya agregado texto a un archivo del cual en la otra rama no haya algun registro de esto, esta fusión te dara los errores y tienes que corregirlos manualmente para que despues de eso se pueda hacer la fusión correctamente.

- i. ¿Cómo puedes ver el historial de tu repositorio?
    - Hay varias formas de ver el historiol de tu repositorio, las mas comunos que se utilizan son los siguientes comandos **git log** y **git log --oneLine**, estos lo que hace es mostrarte el historial de commits que has realizado, el primero de una forma mas completa dantode la fecha, quien lo hizo, y cuando se subio mientras que la otra solamente te muestra los commits y su ID.
    Otra forma de ver el historial es usando el siguiente comando **git log > commits.txt**, esto lo que hace es crear un archivo txt el cual tiene todos los commits que haz hecho, quien los hizo, cuando se hicieron, la hora a la que los hiciero, etc.

- j. ¿Cuál es el propósito de una etiqueta?
    - Las etiquetas se usan principalmente para crear versiones de tu directorio de trabajo, esto se utiliza para marcar si se va a hacer un parche, una actualización pequeña o una grande, la etiqueta esta conformada principalmente por los numeros de version solamente como por ejemplo _**v0.0.1**_, el numero de hasta el final se usa para parches, el de enmedio para actualizaciones pequeñas y el de la derecha para cuando es una actualización grande que pueda cambiar por completo tu aplicación o lo que estes versionando, como por ejemplo _**v1.5.3**_. Las etiquetas se crean con el siguiente comando **git tag numero-versión**.