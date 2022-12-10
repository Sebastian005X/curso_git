** para iniciar un repositorio local se usa **
  git init

** para pasar todo cambios al stage area se usa **
  git add . "esto añade todos los cambios de los archivos"
  git add app.py "solo añade un archivo especifico"

** para guardar los cambioslocalmente **
  git commit -m ""   "en las comillas especificamos la descripción del commit"

** para clonar un repositorio ya existente usamos **
  git clone <"url">

** para ver el estado de mi rama actual **
  git status
  git status -s para mostrarlo de forma corta 

** para sacar archivos fuera del area de stage **
  git restore --staged <"archivo">

** para mostrar de una forma mas detallada lo que has cambiado **
  git diff --staged

** para eliminar archivos de mis commits **
  git rm <'archivo'>

** para mostrar los commits hechos y sus datos **
  git log
  git log --pretty=oneline "para mostrarlo en una sola linea"

** para rehacer cambios de mi ultimo commit **
  git commit --amend "Muestra un editor de codigo para modificar cosas"
  git commit --amend <'valor'> "puedo cambiarle la descripción a mi ultimo commit"
  git commit --amend --no-edit "Me permite añadir (que esten en el stage area) o eliminar archivos en mi ultimo commit"