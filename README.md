### Ejercicio 1


## ¿Qué comando utilizaste en el paso 11? ¿Por qué? 

** git reset --hard HEAD~1" **

Lo usé porque quería mover el puntero una posición hacía atrás del HEAD y fue --hard para perder los cambios del working copy


## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

** git reflog + git reset --hard 7a80f1f " **

Con git reflog busqué el commit anterior y luego git reset --hard 7a80f1f para colocar HEAD allí


## El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?

No hubo conflicto porque la rama styled ya tanía la rama main y los archivos eran iguales


## El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?

Sí porque el fichero git-nuestro.md es tiene distinto contenido en cada rama


## El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?

No hubo conflicto porque el puntero de main estaba en el mismo sitio que styled


## ¿Qué comando o comandos utilizaste en el paso 25?

** git log —graph **


## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

Sí porque no modificamos el texto, solo añadimos un titulo


## ¿Qué comando o comandos utilizaste en el paso 27? 

** git reset HEAD~1 **

## ¿Qué comando o comandos utilizaste en el paso 28?

** git restore git-nuestro.md **


## ¿Qué comando o comandos utilizaste en el paso 29?

** git branch -D title **


## ¿Qué comando o comandos utilizaste en el paso 30?
** git reflog + git reset --hard 15272ad **


## ¿Qué comando o comandos usaste en el paso 32?

** git reflog + git reset --hard d103a93 **


## ¿Qué comando o comandos usaste en el punto 33?

** git reflog + git reset --hard d08d9b2 **