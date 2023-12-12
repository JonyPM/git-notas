# Anotaciones de mis cursos de Git desde 0
[1.4 - Instalacion de Git](https://app.ed.team/cursos/git/01/04)

Nota: es posibles modificar la terminal y agregar frameworks a ella haciendo mas facil el trabajo 
***
[1.5 - Configuracion inicial de Git](https://app.ed.team/cursos/git/01/05)

Comandos de la terminal y su significado:

>cd = Change Dictory (Cambiar de directorio)

>ls = List (Enlistar las carpetas)

>ls -la = List all (Enlista todas las carpetas, incluso las ocultas)

Concepto de git **REPOSITORIO**: es una carpeta que sirve como historial de todos los cambios de se alla echo en git.

Comandos de GIT para la terminal:
>git init (Se utiliza para iniciar un proyecto)
---
[1.6 - Mi primer repositorio](https://app.ed.team/cursos/git/01/06)

Configuracion Basica en GIT:
>git config --global user.name "Nombre-Usuario"

>git config --global user.email "Email-Usuario@gmail.com"

>git config --global core.editor "vim"

config (Te vas a la configuracion de GIT)

--global (Le hablas de forma global a todos los proyectos y todo el sistema operativo, lo guarde para todo)

user.name (Quiero guardar el usuario, su nombre)

user.email (Quiero guardar el usuario, su email)

core.editor (Quiero guardar el tipo de editor de codigo por determinado)(Tipos de editores: Visual Studio, Vim y Nano)

>git config user.name (Para saber que usuario esta registrado)

>git config user.email (Para saber que email esta registrado)

>git config core.editor (Para saber que editor de codigo esta registrado)

Si necesitas saber mas configuraciones ocupa el comando:

>git config --help

**Pendiente : Investigar como unir visual studio con GIT en Windos y Vim con linux.**

---
[1.7 - Mi primer commit](https://app.ed.team/cursos/git/01/07)

Crearemos un **ESTADO** en nuestro **REPOSITORIO**

>git status (Ver el estado de la **RAMA**)

Si has creado nuevos archivos debes guardar los con este comando:

>git add Archivo-Nombre (Para agregar un nuevo archivo a la **RAMA**)

pero tambien cada archivo agregado debe tener su respetivo comentario de los cambios que hicistes:

>git commit -m "Descripcion corta de cambios al archivo guardado"

para revisar la bitacora o historial se puede usar el comando:

>git log

---
Termine la primera parte del curso.

Como trabajo voy a ordenar y estructurar bien mis anotaciones del curso dejando lo mas importante a la vista y lo que no apartarlo eh igual hacer lo mismo con las notas de Markdown
