## COMANDOS BASICOS VI

* Listar el contenido del repositorio de git:

 `git ls-tree master`

 `git ls-tree master^^^`

 `git ls-tree master^3`

* Log en una linea:

 `git log --oneline`

* Log con los tres ultimos commits en una linea:

 `git log --oneline -3`

* Para mas opciones consultar documentacion de git.

## COMANDOS BASICOS VII

  * Examinar el contenido de un commit:

   `git show <id>`

  * Comparar un commit con el actual:

   `git diff <id> nombre_archivo`

  * Comparar dos commits:

   `git diff id..id nombre_archivo`

## RAMAS O *BRANCHES*

  Es la forma para separar la línea actual de desarrollo con respecto

  a la principal. Normalmente representan versiones del software que

  posteriormente son integradas a la línea principal.

## COMANDOS RAMAS I

 * Ver listado de ramas:

  `git branch`

 * Crear una rama:

  `git branch nombre_rama`

 * Cambiarnos a una rama:

  `git checkout nombre_rama`

 * Crear una rama y moverse en un paso:

  `git checkout -b nombre_rama`

 * Comparar ramas:

  `git diff nombre_rama..nombre_rama`

## COMANDOS RAMAS II

 * Ver ramas identicas a la actual:

  `git branch --merged`

 * Renombrar ramas:

  `git branch -m nombre_antiguo nombre_nuevo`

 * Eliminar ramas:

  `git branch -d nombre_rama`

  `git branch -D nombre_rama`

 * Integrar ramas a la actual:

  `git merge nombre_rama`

 * Resolver conflictos (se suele hacer manualmente):

  `git merge --abort`
