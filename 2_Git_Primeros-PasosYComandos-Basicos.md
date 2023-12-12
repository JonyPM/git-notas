# Anotaciones de mis cursos de Git desde 0
[2.1 - Conceptos importantes y las 3 áreas de Git](https://app.ed.team/cursos/git/02/01)

Bitacora = Repositorio

Las 3 areas de Git: 

1- Working directory (Directorio de trabajo)
>Git add Nombre-Archivo 

2- Stage area (area de preparacion)

Es un estado simbolico
>Git commit -m "comentario"

3- Local Repository (Repositorio)

---

[2.2 - Usando las areas de Git](https://app.ed.team/cursos/git/02/02)

1- Working directory

Agrega, Edita y elimina archivos
>Git status

2- Stage area

Se revisa el estatus y los cambios de los archivos
>Git add Nombre-Archivo

3- Local Repository 

La ultima fase es comentar sobre los cambios guardados
>Git commit -m "Comentario"

Revisar el repositorio 
>Git log

---
[2.3 - Stage y Comit](https://app.ed.team/cursos/git/02/03)

Comando nuevos 

>git add .

Agrega todo los archivos y carpetas de donde estas parado en el directorio.

>git add -a

Agrega todo archivo y carpeta que no este agregado al Area de preparacion no importa en que parte del directorio estes.

---
[2.4 - Revirtiendo cambios](https://app.ed.team/cursos/git/02/04)

Comando para quitar un archivo en el area de preparacion.

>git restore --staged NombreArchivo

Comando para revertir los cambios.

>git checkut NombreArchivo

---
[2.5 - Entendiendo los Commits y el Log](https://app.ed.team/cursos/git/02/05)

Para referirse a un Comentario en Git puedes usar solo los primeros 6 o 7 digitos del commit.

Comando para ver espesificamente un comentario, buscandolo con su id.
>git show ID (Cantidad X del id)

Comando para ver el git log en una sola linea.
>git log --oneline

Comando para ver en una sola linea un archivo que solo se alla modificado.
>git log --oneline NombreArchivo

Comando para ver en una sola linea los comentarios que ah echo cierto autor.
>git log --oneline --author="NombreAutor" 

Comando para buscar en los comentarios ciertas palabras claves.
>git log --grep="PalabraCualquiera"

Saber manejar de maravilla los commit y los log nos ayudara para movernos en los registros de los archivos.