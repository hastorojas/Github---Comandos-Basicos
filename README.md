# Github<!-- omit in toc -->

## Comandos basicos para Github by hastorojas<!-- omit in toc -->

* `git add [archivo]` Agrega los archivos al Stage
* `git rm --cached [archivo]` Quita el archivo del Stage
* `git add -A`: 	Agrega todos los archivos al Stage
* `git rm -f [archivo]` Quita los archivos del Stage y los borra
* `git commit -m "[mensaje]"` Agrega nuestro archivo al Repositorio, mensaje para saber que se hizo ejm. 'Iniciar nuestro landing'
* `git log`	Muestra el historial de todos los commit que se han realizado
* `git log --oneline`	Version resumida del historial
* `git commit --amend` Anexa un cambio que hayamos olvidado al último commit
* `git tag -a [version] -m "[mensaje]"`	Crea un tag (etiqueta) a el último commit realizado
* `git tag [version] hash` Crea un tag a un hash especifico
* `git tag -l` Muestra todos los tag
* `git tag -d [version]` Elimina versiones
* `git branch [nombre]` Crea una nueva rama (Master también se considera una rama)
* `git branch -l` Lista todas las ramas que tienes
* `git branch -d`	Borra la rama si esta esta vacía
* `git branch -D` Borra la rama aún así esta contenga información
* `git branch -m [NombreActual][NombreNuevo]` Cambia de nombre a una rama
* `git config --list` Muestras todas las propiedades que git a configurado
* `git checkout` Cambia entre ramas y temporalmente entre los hash1
* `git checkout -b [rama]` Crea una nueva rama y se va directamente a ella
* `git merge [rama]` Trae los cambios de la rama que indiquemos a la rama master
* `git stash` Guarda los cambios en un limbo para que solo en la rama que estemos lo veamos
* `git stash list` Muestra todos los stash que tenemos guardado
* `git stash apply` Aplicamos el ultimo cambio, listos para que las demas ramas lo vean
* `git stash apply [nom]` Aplicamos el cambio del stash que indiquemos
* `git cherry-pick [hash1]` Trae el commit de una rama a otra
* `git reset --soft`	Quita un cambio, pero lo mantiene en el stage
* `git reset --mixed`	Quita un cambio, lo quita del stage, los mantiene en el working directory
* `git reset --hard`	Quita un cambio, los borra totalmente, pero si tienes guardado el hash1, lo puedes recuperar
