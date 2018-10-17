## Comandos Ramas III ##

* Almacenar cambios temporales

 `git stash save "Mensaje"`

* Listar cambios

 `git stash list`

* Ver contenido de un cambio temporal

 `git stash show -p nombre_stash`

* Eliminar un cambio temporal:

 `git stash drop nombre_stash`

* Aplicar cambio del stash:

 `git  stash  apply  nombre_stash`

 `git  stash  pop  nombre_stash`

## Comandos Github I ##

* Añadir repositorio remoto

 `git remote add origin url`

* Ver repositorios remotos:

 `git remote -v`

* Eliminar repositorio remoto:

 `git remote rm origin`

* Añadir cambios del repositorio local al remoto:

  `git push -u origin master`

* Añadir cambios del repositorio remoto al local:

 `git pull`


## Comandos Github II ##

* Ver branches remotos:

 `git branch -r`

* Ver todos los branches:

 `git branch -a`

* Clonar un repositorio remoto:

 `git clone url`

## Dar seguimiento a branches remotos ##

* LOCAL a REMOTO

  * Cambios en el repositorio local.

  * Commit de los cambios.

  * Añadir cambios a repositorio remoto:

 `git push`

* REMOTO a LOCAL

  * Sincronizacion y union:

 `git fetch origin`

 `git merge origin/master`

  * En un solo paso:

 `git pull`

## Operaciones con branches remotos ##

* Creacion:

 * Crear branch local.

 *Hacer cambios en dicho branch.

 * Hacer commit.

 *Copiar el branch al repositorio remoto:

 `git  push -u origin  branch_remoto`

* Copia:

 `git  checkout  -b local  remoto`

* Eliminacion:

 `git  push  origin  --delete  branch_remoto`
