# Comandos básicos Git

git -v (Versión de Git)


git init (Creará un nuevo repositorio local GIT)

	- Usará como nombre el directorio en el que estemos

	- Para especificar un nombre usaremos git init [nombre]


git clone (Copiar un repositorio)

	- Si está en un servidor remoto: git clone nombredeusuario@host:/path/to/repository

	- Para copiar un repositorio actual: git clone /path/to/repository


git add <holamundo.txt> (Agregar archivos al área de preparación)


git commit -m "Mensaje" (Creará una instantánea de los cambios y los guardará en el directorio git)


git status (Lista de archivos que se han cambiado junto a los que están por ser preparados o confirmados)


git push (Para enviar confirmaciones locales a la rama maestra del repositorio remoto)

	- La estructura básica es: git push origin <rama_a_la_que_enviar_datos>


command git checkout -b <rama> (Crea una rama y se cambia a ella)


git checkout <rama> (Cambia a la rama)


git pull (Fusiona los cambios hechos en el repositorio)


git merge <rama> (Se usa para fusionar una rama con otra rama activa)


git diff (Ver los conflictos presentes)



Orden para guardar cambios:

git add CMDS.md

git commit -m "Añadidos comandos git"

git push
