1.- Un pull request es una peticón de cambios que se realiza en github y la cual el receptor y dueño del directorio a modificar debe aceptar.
2.- Un conflicto de fusión o merge conflict ocurre al fusionar dos ficheros o dos ramas y se suele resolver manualmente abriendo el editor de texto puesto que git bash te dice donde han podido surgir los conflictos.
3.- Primero es necesario estar en una de esas ramas, para lo que utilizamos git checkout main, y posteriormente utilizamos git merge examen_parcial para fusionar la rama, si surgen conflictos debemos resolverlos manualmente y posteriormente añadir los cambios al indice con git add . y dejar constancia de los cambios con git commit -m y un nombre significativo.ç
4.- Utilizaría git rebase para dirigirme al anterior commit, pero primero utilizaría git log --oneline para ver la lista de commits con sus respectivos números identificadores.
5.- Un fork se realiza desde un repositorio en github simplemente pulsando el botón que aparece en la parte superior derecha de la pantalla, este sirve para copiar el repositorio a tu cuenta de git hub y normalmente va seguido de un git clone con el enlace al repositorio para editar este en la shell de git.
6.- A) Realizaría un cd Universidad y posteriormente un cd UAX, donde se encuentra el archivo.txt, si quisieramos también abrirlo y editarlo deberíamos hacer un nano archivo.txt. Todo esto son rutas relativas puesto que solo avanzamos un paso .
B) En este caso solo habría que ejecutar un cd UAX y en este caso sería a su vez una ruta relativa y una ruta absoluta puesto que solo es necesario moverse un paso para llegar a donde queremos, sin embargo en estos casos se suele decir que la ruta es absoluta.
7.- 
1) b, git clone
2) b, git checkout
3) c, git checkout
4) b, git add
5) b, git commit
6) b, git push
7) c, git pull
8) d, git merge
9) a, git reset -hard
10) c, git log
8.- Para empezar crearía una nueva rama con git checkout -b "nombre" para asegurarme de respetar ambas ramas, luego mergearía las dos ramas en dos pasos, git merge matemáticas, donde no debería haber errores, y posteriormente git merge Diseño UX en el que resolvería los conflictos si los hubiera y registraría los cambios en el índice con git add . y haría un git commit -m con un nombre significativo, entonces me iría a la rama develop con git checkout develop y mergearía la nueva rama con git merge nombre asegurandome nuevamente de resolver los conflictos de forma manual y añadiendo los cambios al índica got git add . y git commit -m "nombre significativo". De esta forma no pasaría nada si hubiese algún fallo aunque hayamos tenido mucho cuidado puesto que podríamos acceder al c los commits anteriores donde no están guardados los nuevos cambios.
9.- C
