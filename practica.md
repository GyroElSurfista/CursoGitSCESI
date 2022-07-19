# Esta es la práctica de la SCESI :D

## ¿Qué es Git?

<img src = "Images/gitlogo.png" width="588" height="200">

Git es un sistema de control de versiones que permite registrar los diferentes cambios que se realizan en un proyecto.

- ### Repositorio. - 

    <img src = "Images/directory_icon.png" width = "200" height = "200" >

    Un repositorio es un directorio al cual Git le está haciendo seguimiento. Para que git realice dicha tarea, se debe dirigir a la carpeta en cuestión y utilizar el comando:
    ~~~~
    git init
    ~~~~
    

- ### Areas

    1. #### Working area
        El working area es aquel en el cual se manipulan los archivos (se realizan cambios).
    2. #### Staging area
        El staging area es aquel en el cual se agregan los archivos a los que se les quiere realizar un commit. Para enviar cambios realizados al staging area se debe emplear el comando:
        ~~~~
        git add <nombre del archivo modificado>
        ~~~~
    3. #### Git area
        El git area es aquel en el cual se tienen almacenados todos los commits del repositorio.

- ### Commit. - 

    <img src ="Images/writing-down.png" width = "240" height = "240">

    Un commit es el registro de un cambio realizado en un determinado repositorio. Todo commit es realizado manualmente y debe incluir una breve explicación de lo sucedido.

- ### Ramificar y Fusionar (Branch and Merge) 

    <img src = "Images/branching.png" width = "410" height = "200">


    La ramificación y la fusión son una carácterística muy util de git pues permite el trabajo de manera paralela. Un repositorio está estructurado como un arbol que tiene diferentes ramas. La rama principal de este arbol es llamada master. A partir de cada rama se puden crear nuevas (al momento de crear una rama esta contiene todos los commits de su rama origen) estas ramas se pueden usar para desarrollar una carácteristica nueva, experimentar o también para independizar el trabajo de cada miembro del equipo de desarrollo, los cambios hechos en una rama no afectan a la origen. Las ramas existen para que en algún momento vuelvan a ser acopladas entre ellas, esta acción es denominada "fusión" o "merge", una fusión consiste en unir los cambios realizados en las ramas participantes.

    #### Comandos para Ramificación y Fusión:

    - git branch. - Permite ver el árbol del repositorio.

    - git branch [ rama ]. - Crea la rama 'rama'

    - git checkout [rama destino] Permite desplazarnos entre ramas.

    - git merge [rama ]. - Permite fusionar la rama 'rama' a la actual.