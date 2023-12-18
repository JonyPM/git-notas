# Cuarto Bloque mi curso de Git desde 0

[4.1 - Si hay ramas locales: ¿Hay ramas remotas?](https://app.ed.team/cursos/git/04/01)

Empezamos a registrarnos en github y gitlab

---
[4.2 - Git en la nube: GitHub y GitLab](https://app.ed.team/cursos/git/04/02)

Vimos como crear un repositorio

---
[4.3 - Creando nuestro primer proyecto en Github](https://app.ed.team/cursos/git/04/03)

Comandos para la sincronizacion con la nube en GitHub

Comando para verificar si el git esta conectada con algun repositorio en la nube

>git remote -v

Comando remoto para agregar un repositorio de la nube a git
>git remote add origin https://github.com/JonyPM/git-notas.git

(Por estandar siempre el primer repositorio se le llama **Origin**)

Para subir un repositorio desde el escritorio a la nube requieres del nombre de usuario de git y generar un token de seguridad.
>git push origin NombreDelDirectorio 

**Push** significa empujar o mandar datos.
**Fetch** significa jalar o traer informacion.

---
[4.4 - Dashboard de proyecto en Github](https://app.ed.team/cursos/git/04/04)

**Consejo de buena practica:**Recomiendo que subas todas las ramas de tu terminal a GitHub.

>git push origin NombreRama

---
[4.5 - Sincronizando y mezclando ramas](https://app.ed.team/cursos/git/04/05)

Este comando tambien sirve para act---
4.6 - Ignorando archivos y clonando repositorios
ualizar los origin de la nube con las ramas locales.
>git push origin NombreRama

Podemos agregar cambios de una rama a otras ramas en git solicitando un pull requests.

Este comando sirve para buscar los cambios de la nube a la terminal.
>git fetch 

Este comando sirve para acutalizar los cambios de la nube a la terminal.
>git pull origin NombreRama

---
[4.6 - Ignorando archivos y clonando repositorios](https://app.ed.team/cursos/git/04/06)

Tipo de archivo de git: 
>.gitignore

Puedes agregar nombres de *archivos* o de *carpetas* en el archivo .gitignore para que git lo ignore, Nota: si ya seguia el archivo debes de eliminar el **Cache**.

**Consejo**: si guardas el archivo con 
>git commit 

se te desplegara otra interfas, si le das a la tecla (i) podras escribir ese nuevo commit, despues darle la tecla (Esc) y (WQ) para salir y guardar los cambios.

La palabra **Clonar** se utiliza cuando se copia un repositorio a una nueva computadora.

Comando para clonar un repositorio
>git clone CopiaDirectorio

Si algun motivo el comando Fetch no te jala los suficientes datos de la nube puedes utilizar este comando.
>git ls-remote

creara un listado de lo que tiene la nube y no ten tu computadora.

despues de saber que ramas estan listadas en el remote puedes ocupar este comando para verlas todos
>git branch -a


Para saber los datos de todas las ramas de un directorio puedes ocupar este comando
>git fetch --all

Video que me ayudo a incorporar git bash al editor de codigo Visual Studio Code:

[Instalación e Incorporación de Git Bash en Visual Studio Code](https://www.youtube.com/watch?v=eQ84h0Eau9I&list=PLIfxGB0e49nKIQk70V7967I0nVLKsD5SN&index=1)

--- 