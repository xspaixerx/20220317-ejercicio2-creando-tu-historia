Ejercicio 2
===========

[ ] Crea una carpeta denominada S2R1. Realiza las siguientes acciones en ella:

[ ] Crea un repositorio Git.

[ ] Crea un fichero denominado actores.txt. Añade tres nombres de actores cada uno en una línea distinta.

[ ] Haz un primer commit.

[ ] Crea una rama denominada test.

[ ] Cambia a la rama test

[ ] En la rama test crea un fichero denominado actrices.txt. Añade tres nombres de actrices y realiza un commit en dicha rama.

[ ] Haz una captura de pantalla del resultado del comando git log --graph --all (y los parámetros que consideres).
![image](https://user-images.githubusercontent.com/99899320/158852167-9976c8b5-193c-4af3-9935-cd70fabee39e.png)


[ ] Cambia a la rama master.

[ ] Incorpora los cambios de la rama test a la rama master. Haz una captura de pantalla de los comandos que has utilizado y de su resultado.
![image](https://user-images.githubusercontent.com/99899320/158852782-487eba24-048c-4480-ac00-236dcb58a65a.png)


[ ] Crea una segunda rama denominada test2. La rama test2 apunta al mismo commit que la rama master en este momento.

[ ] En la rama master, añade una actriz al fichero actrices.txt y haz un commit.

[ ] Cambia a la rama test2

[ ] En la rama test2, añade una actriz al fichero actrices.txt y haz otro commit.

[ ] Haz una captura de pantalla del resultado del comando git log --graph --all. Debe haber dos caminos distintos: uno para la rama master y otro para la rama test2.
![image](https://user-images.githubusercontent.com/99899320/158855005-477c76d7-3d47-4e62-a23a-6f35ba3da259.png)


[ ] Cambia a la rama master.

[ ] Incorpora los cambios de la rama test2 a la rama master. ¿Se produce un conflicto? De ser así realiza una captura del comando git status.
![image](https://user-images.githubusercontent.com/99899320/158855247-044139ba-751e-4e42-b9ac-f73cde7246ab.png)


[ ] Resuelve el conflicto incorporando los dos nombres de actrices.
![image](https://user-images.githubusercontent.com/99899320/158857841-0d3caa4c-7309-461e-beca-db1c17caa836.png)
![image](https://user-images.githubusercontent.com/99899320/158858046-4bf9f109-8af0-4e29-a537-b13139382e0b.png)


[ ] Haz una captura de pantalla del resultado del comando git log --graph --all. Observa que se ha creado un nuevo commit que integra los dos caminos anteriores.
![image](https://user-images.githubusercontent.com/99899320/158857923-e9c3f383-b121-45bb-b6ef-ef725fe2974d.png)


