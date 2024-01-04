# Quinto Bloque mi curso de Git desde 0

[5.1 - GitHub Desktop](https://app.ed.team/cursos/git/05/01)

Utilizando git mediante una interfaz grafica en vez de la terminal

Instala Github desktop y lo configura

---
[5.2 - Manejando repositorios con GitHub Desktop parte 1](https://app.ed.team/cursos/git/05/02)

Se vieron estos comandos en el video 
>git switch test

>git merge dev

>git push origin test

>git switch master

>git merge test

>git push origin master

[5.3 - Manejando repositorios con GitHub Desktop parte 2](https://app.ed.team/cursos/git/05/03)

Crea una nueva rama (fix/readme) en la interfaz de github
>git branch -c fix/readme

Acutaliza los datos
>git fetch

Empuja los datos de la nube a la terminal
>git pull origin dev

Elimina la carpeta
>git branch -d fix/readme

---
[5.4 - Manejando-repositorios con GitKraken](https://app.ed.team/cursos/git/05/04)

instalacion de gitkraken 

Crea una nueva rama (feature/about-page) en la interfaz grafica de gitkraken y lo elimina

---
[5.5 - Visual studio code y Git](https://app.ed.team/cursos/git/05/05)

Instalacion de una extencion en visual llamada gitlens pro (trial) que ocupa la misma interfaz grafica de gitkraken

---
[5.6 - Tips adicionales de git y Github](https://app.ed.team/cursos/git/05/06)

Comando para generar etiquetas en una rama, comunmente se utilizan para colocarle la version a una rama, ejemplo : git tag v1.0.1
>git tag NombreTag 

y para subirlo a github se utiliza el comando 
>git push origin v1.0.1

ayuda a controlar las versiones con github y poder descargar una version de tu programa en github como archivo zip o tar.gz

Un tip para github es editar directo en la nube oprimiendo . dentro de git

Comando para fucionar(rebase) dos archivos
>git config pull.rebase false

despues de hacer eso git te dara los dos codigos que se iban a fusionar y tu tendras que elegir que es lo que se va a quedar y cual se va a ir
