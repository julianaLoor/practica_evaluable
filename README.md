# practica_evaluable

Hemos aprendido a coger soltura a través de este ejercicio utilizando comandos para:
- Crear documentos
- Crear archivos
- Añadir texto a los archivos
- Ponerlos en estado de preparación
- Guardar los cambios a través de los commits
- Tener acceso al historial de commits
- Poder resetear o revertir cambios.
- Clonar archivos.

Por otra parte, hemos aprendido a utilizar ramas y a clonar repositorios que pueden ser útiles en un futuro en caso de trabajar en equipo.
También hemos aprendido a crear etiquetas.

En cuanto a la edición, siempre podemos volver a un estado anterior añadiendo más texto, pero es necesario recordar que cada modificación ha de pasarse al estado de preparación antes de guardar los cambios.

Otro de los puntos relevantes es la sincronización entre trabajar en local y trabajar en remoto y luego poder subir los cambios de los repositorios al remoto.

Entre los comandos más utilizados:
- mkadir
- ls -la, para ver lo que contiene nuestra carpeta/directorio
- echo tanto ficheros y añdir texto
- gid add . para ponerlos los ficheros en estado de preperación
- git commit -m, guardar los cambios con comentarios
- git reset hash, para volver a un estado de un commit a través de su identificador
- git revert HEAD para revertir el último commit
- git log --oneline para ver el historial de los commits, además permite ver los identificadores (hash) de cada uno de ellos
- gir remote set-url enlace, para conectar un repositorio remoto con el local
- git checkout para cambiar de ramas
- git status para ver el estado del working
- git remote -v
- git push
- git branch
- cat para ver el contenido de los documentos con sus modificaciones
- git merge rama rama para fusionar
