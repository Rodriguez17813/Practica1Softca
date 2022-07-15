Esté es un archivo de prueba y practica sobre Git

14 de julio 2022

Lista de comandos usados

1) git init: inicializar el repositorio
2) git add nombre_de_archivo.extensión: agregar el archivo al repositorio
3) git commit -m “Mensaje”: Agregamos los cambios para el repositorio
4) git add: Agregar los cambios de la carpeta en la que nos encontramos agregar todo
5) git status: visualizar cambios
6) git log nombre_de_archivos.extensión: histórico de cambios con detalles
7) git push: envía a otro repositorio remoto lo que estamos haciendo
8) git pull: traer repositorio remoto
9) ls: listado de carpetas en donde me encuentro. Es decir, como emplear dir en windows.
10) pwd: ubicación actual
11) mkdir: make directory nueva carpeta
12) touch archivo.extensión: crear archivo vacío
13) cat archivo.extensión: muestra el contenido del archivo
14) history: historial de comandos utilizados durante esa sesión
15) rm archivo.extensión: Eliminación de archivo
16) comando --help: ayuda sobre el comando
17) git checkout: traer cambios realizados
18) git rm --cached archivo.extensión: se utiliza para devolver el archivo que se tiene en ram. Cuando escribimos git add, lo devuelve a estado natural mientras está en staging.
19) git config --list: muestra la lista de configuración de git
20) git config --list --show-origin: rutas de acceso a la configuración de git
21) git log archivo.extensión: muestra la historia del archivo
22) git diff "codigo de las versiones a comparar"
23) git reset HEAD: nos ayuda a sacar los archivos del estado staged para devolvelos a su estado anterior
--------- Los 4 estados de git --------
Untracket: el archivo no vive en git, solo en el disco duro
Unstaged: son archivos que git tiene registros de sus cambios pero estan des-actualizados
Staged: archivos que han sido enviados a staging con git add.
Tracket: los archivos viven dentro del repositorio, estan actualizados y no tienen cambios pendientes