# Cuestionario

A) ¿Qué comando utilizaste en el paso 11? ¿Por qué?

> `git reset --hard HEAD~1`

> Porque es la manera de borrar el commit sin dejar nada, si se dejara algo en el staying area seria con soft.

B) ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?    

> 'git reset d18f9fe'

> Para rehacer el commit completo que acababa de borrar.

C) El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 

>No causo conflicto pero no se puede hacer porque styled ya contiene la rama main completa en este punto.

D) El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

>Si, porque los archivos en las ramas que se combinaorn estaban editados disferente.

E) El merge del paso 20, ¿Causó algún conflicto? ¿Por qué?

>No, no crea conflicto porque sube main

F) El merge del paso 24, ¿Podría ser fast forward? ¿Por qué? 

>No porque la rama de la que nace tendria quetener algun cambio tambien.

G) ¿Qué comando o comandos utilizaste en el paso 25?  

>git reset HEAD~1

H) ¿Qué comando o comandos utilizaste en el paso 26?  

>git checkout -- nombre del archivo

I) ¿Qué comando o comandos utilizaste en el paso 27? 

>git branch -D title

J) ¿Qué comando o comandos utilizaste en el paso 28?  

>git merge 02602f0

K) ¿Qué comando o comandos utilizaste en el paso 30? 

>git lg
>git checkout 3301dd9
>git tag initial
>git lg
>git checkout 49d214
>git tag styled
>...