
# Chuleta de Git

## Consultar el estado y el historial

- `git status`: muestra los cambios pendientes.
- `git log --oneline`: muestra el historial resumido.
- `git diff`: muestra cambios no preparados.
- `git diff --cached`: muestra cambios preparados.

## Preparar y confirmar cambios

- `git add archivo`: prepara un archivo.
- `git add .`: prepara todos los cambios del directorio actual y sus subdirectorios.
- `git commit -m "mensaje"`: guarda un commit con un mensaje.

## Deshacer cambios

- `git restore archivo`: descarta cambios no preparados del archivo.
- `git restore --staged archivo`: quita el archivo del área de preparación, sin borrar sus cambios del directorio de trabajo.

## Archivos

- `git mv antiguo nuevo`: renombra o mueve un archivo bajo control de Git.
- `git rm archivo`: elimina un archivo y prepara su eliminación.
- `git rm --cached archivo`: deja de seguir un archivo, pero lo conserva localmente.

## Ramas y fusiones

- `git branch`: lista las ramas locales.
- `git switch -c nombre-rama`: crea y cambia a una rama.
- `git switch main`: cambia a `main`.
- `git merge nombre-rama`: fusiona una rama en la rama actual.

## GitHub

- `git remote -v`: muestra los repositorios remotos configurados.
- `git push -u origin nombre-rama`: sube una rama al remoto.
- `git pull`: descarga e integra cambios de la rama remota configurada.
