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

---
[3.4 - Ejercicio completo con ramas parte 1](https://app.ed.team/cursos/git/03/04)

**Consejo de buena practica:** La rama Master es la que debe tener la version que oficialmente se va a mostrar a al cliente.

**Consejo de buena practica:** Debes de trabajar con *Ramas Temporales* (que despues de usar las se tendran que eliminar), la rama principal, test y dev seran ramas que nunca vas a tocar, eliminar o trabajar en ellas (Solo serviran como un respaldo).

**Consejo de buena practica:** Las Ramas Temporales deben de tener una nomeclatura clara como, feat o feature (freactura) + / + La pagina que va a crear esa rama como una pagina de contacto para tu portafolio.

[3.5 - Ejercicio completo con ramas parte 2](https://app.ed.team/cursos/git/03/05)

**Consejo de buena practica:** Si te piden reparar un error de las Ramas Principales, como buena practica deberias crear una rama temporal con nomeclatura que se explique que es lo que se esta haciendo.
**Ejemplo:** fix/title-color (Reparacion en el color del titulo)

**Consejo de buena practica:** La rama TEST solo va a recibir cambios unicamente de la rama DEV

[3.6 - Ejercicio completo con ramas parte 3](https://app.ed.team/cursos/git/03/06)

Si guardas un archivo atrazado puesde que se te cree un archivo ya sea con visual studio o con vim (Si es con vim ocupa el codigo :WP)
