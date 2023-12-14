# Tercer anotacion de mi curso de Git desde 0
[3.1 - Que son las ramas](https://app.ed.team/cursos/git/03/01)

comando para ver graficamente la rama
>git log --oneline --graph

La rama inicial es la que es llamada como **Master** pero para no generar polemicas hoy en dia se le denomina Rama **Main** o Rama Principal

Puntos del video 

* Tenemos la rama principal
* Se pueden crear otras ramas apartir de la rama principal
* Las otras ramas pueden llevar commits en sus ramas

---
[3.2 - Creando y usando ramas](https://app.ed.team/cursos/git/03/02)

Comando para saber en que rama estas colocado de la linea de tiempo
>git branch

Comando para crear una nueva rama
>git checkout -b NombreRama

tambien se puede usar, (-c = Create) 
>git switch -c NombreRama

los de Git se quiere estandarizar el uso del **Switch**

Comando para regresar a la rama principal
>git checkout master

Comando para eliminar una rama, (-d = Delete) 
>git branch -d NombreRama 

---
[3.3 - Fusionando ramas](https://app.ed.team/cursos/git/03/03)

Comando para ver los cambios de dos ramas (diff = Diferent)
>git diff NombreRamaSuperior

Comando para anidar dos ramas (merge = Unir)
>git merge NombreOtraRama

se unira a una con la rama que estas actualmente.

**Consejo de buena practica:** Como buena practica la rama principal nunca debe de estar por encima de las ramas secundarias