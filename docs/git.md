# Git como usarlo
existen 2 tipos de repositorio por decirlo se una manera

- **local**: en este los cambios se guardaran solo en el equipo. 
- **online**: este tipo trabaja junto con el local, el cual guarda los cambios locales y permite compartirlo con otros usuarios.


## Crear repositorio local

para crear un repositorio hay que estar primero dentro
de la capeta con tu terminal de preferencia y ejecutar el siguiente codigo

`git init`

este creara un repositorio local
la evidencia de que funcione es que 
aparesca una carpeta oculta con el nombre *.git*
## Guardar cambios local

cuando generas un repositorio o haces un 
cambio tienes que guardar esos cambios o archivos nuevos,
para eso tienes que usar el comando `git add [archivo]`
tambien puede ser toda una carpeta, pero si quieres guardar todo
sin importar que sea usa el comando `git add -all` o tambien puedes usar `git add -A`

Una vez creado tienes que comentar el archivo
### borrar cambio guardado
`git restore --staged [archivo]`

### Generar Commit

el commit nos permite anotar los cambios y saber que se hizo en ese archivo
lo recomensable es hacer un comit, para cada archivo subido por add sino agregara a todos bajo el mismo commit

el comando a utilizar es `git commit -m "[Comentario]"` ya esta listo para subir el archivo al repositorio.

## Repositorio Online

Pasa subir archivos al repositorio que pude ser en [GitHub](https://www.github.com/) o [GitLab](https://about.gitlab.com). 


### Conectar Repositorio
usando este comando para conectar tu local al repositorio en [GitHub](https://www.github.com/) o [GitLab](https://about.gitlab.com). 

`git remote add [alias]`

por lo general el nombre del alias es **origin** pero puedes usar cualquier nombre para la conexion.
#### Eliminar Conexion
En caso de que te equivoques o cualquier fallo puedes borrarlo con el comando:

`git remote remove [conexion]`

Ejemplo que el nombre de la conexion sea origin: `git remote remove origin`

### Subir commit al repositorio

`git push [conexion] [rama]`

este subira todos los commit al archivo origin
## Estado y informacion de ramas

Informacion de la rama

- **Historia del repositorio:** `git log --all --decorate --oneline --graph`
- **Estado del local:** `git status`
- ****

## vover 
`git reset [codigo comit]`
