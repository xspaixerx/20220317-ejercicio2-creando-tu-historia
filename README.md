Ejercicio 2
===========

[ ] Crea una carpeta denominada S2R1. Realiza las siguientes acciones en ella:
[ ] Crea un repositorio Git.
[ ] Crea un fichero denominado actores.txt. Añade tres nombres de actores cada uno en una línea distinta.
[ ] Haz un primer commit.
[ ] Crea una rama denominada test.
[ ] Cambia a la rama test
[ ] En la rama test crea un fichero denominado actrices.txt. Añade tres nombres de actrices y realiza un commit en dicha rama.
[ ] Haz una captura de pantalla del resultado del comando git log --graph --all.
[ ] Cambia a la rama master.
[ ] Incorpora los cambios de la rama test a la rama master. Haz una captura de pantalla de los comandos que has utilizado y de su resultado.
[ ] Crea una segunda rama denominada test2. La rama test2 apunta al mismo commit que la rama master en este momento.
[ ] En la rama master, añade una actriz al fichero actrices.txt y haz un commit.
[ ] Cambia a la rama test2
[ ] En la rama test2, añade una actriz al fichero actrices.txt y haz otro commit.
[ ] Haz una captura de pantalla del resultado del comando git log --graph --all. Debe haber dos caminos distintos: uno para la rama master y otro para la rama test2.
[ ] Cambia a la rama master
[ ] Incorpora los cambios de la rama test2 a la rama master. ¿Se produce un conflicto? De ser así realiza una captura del comando git status.
[ ] Resuelve el conflicto incorporando los dos nombres de actrices.
[ ] Haz una captura de pantalla del resultado del comando git log --graph --all. Observa que se ha creado un nuevo commit que integra los dos caminos anteriores.
