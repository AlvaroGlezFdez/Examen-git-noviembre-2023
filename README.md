Álvaro González Fernández
link https://github.com/AlvaroGlezFdez/Examen-git-noviembre-2023

# Examen-git-noviembre-2023
PREGUNTA 1:
Un pull request es un proceso de git y github clave en el flujo de trabajo cooperativo de un proyecto. Este proceso te da la capacidad de poder hacer tu propia propuesta de mejora o proponer cambios a un proyecto sin realmente realizar un cambio en el repositorio original. Resumidamente, para hacer un pull request primero se necseita hacer un fork del repositorio original, clonar este repositorio mediante un git clone y crear una rama donde comenzarás a introducir tus propuestas y cambios. A continuación, realizas estos cambios con sus respectivos commits y es turno de sincronizar tu rama con el repositorio original mediante un git pull (arrastrando información y fusionándola con tu rama) y un git merge (para fusionar las ramas). Por último se realiza el git push y solo quedaría esperar a que nuestro pull request sea aceptado o rechazado por el dueño del repositorio o proyecto.
PREGUNTA 2:
Un conflicto ocurre en git cuando, al fusionar dos ramas, se produce un error ya que existen datos diferentes en el mismo espacio del mismo archivo. Para solucionarlo simplemente necesitarías borrar los caracteres con los que git te avisa de la existencia de un conclito como "<<<<<<<<<", "========" o ">>>>>>>". 
PREGUNTA 3:
Para fusionar correctamente esas dos ramas únicamente nos deberemos fusionar en la rama de examen_parcial y realizar un git merge main. Después se deberán resolver los conflictos en caso de que existiesen.
PREGUNTA 4: 
Para ello utilizaremos el comando "git log --oneline" , de esta manera podremos acceder al historial de commits realizados con anterioridad y retoceder accediendo a ellos.
PREGUNTA 5:
Para realizar un fork primero nos deberemos situar en el repositorio sobre el que queramos realizar ese (desde Github) y ya desde ahí nos da la opción de "realizar un fork". Comunmente, este es el primer paso utilizado en el "pull request" ya que de esta forma podemos acceder y modificar un reposiorio en nuestro área de trabajo (working area) sin realmente afectar al repositorio original.
PREGUNTA 6 APARTADO A:
Para acceder a este archivo llamado "archivo.txt" tenemos dos formas de hacerlo: la primera de ellas sería usando repetidamente el comando "cd" el cual nos permite movernos por los directorios. El proceso consistiría en hacer "cd Álvaro Gonázlez", seguido de "cd Universidad", despúes "cd UAX" y por útlimo realizar un "nano archivo.txt" ya que este último es un archivo y no un directorio, por lo que no se puede ulilizar un "cd". Digamos que esta sería la manera larga de hacerlo, ya que si conocemos perfectamente la ubicación de "archivo.txt" podríamos simplificar los 3 "cd" que hemos realizado en tan solo 1, de tal forma que nos quedaría "~/Álvaro González/Universidad/Uax" y de esta forma tan solo nos quedaría hacer el "nano archivo.txt". Esta última manera es un caso de ruta absoluta ya que conocemos exactamente donde se enuentra el archivo al que queremos acceder y metemos el comando desde el directorio raíz (/).
PREGUNTA 6 APARTADO B:
Si nos encontramos ya dentro del directorio "Universidad" simplemente haríamos "cd UAX" y "nano archivo.txt". A diferencia de el caso anterior, partimos desde el directorio "Universidad" y no desde el directorio raíz, por lo que hablamos de una ruta relativa.
PREGUNTA 7:
1- Git clone
2- Git branch
3- Git checkout
4- Git add
5- Git commit
6- Git push
7- Git pull
8- Git merge
9- Git reset
10- Git log

PREGUNTA 8:
Para la correcta integración de ambos cambios en las distintas ramas, el principal problema podrían ser los conflictos que se pueden dar, por lo que el proceso sería fusionar ambas ramas (por separado) con la rama main mediante primero el git pull (sincronizando la rama para asegurar que se encuentra actualizada) y despúes un git merge main y, en caso de que sujan conflictos, resolverlos mediante la eliminación de los caracteres "<<<<<<<", "=======" o ">>>>>>>".
PREGUNTA 9:
respuesta C.
