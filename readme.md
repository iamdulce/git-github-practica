# Práctica de Git y Github

## Ejercicio 1

- **¿Qué comando usaste en el paso 11? ¿Por qué?**
`reset -- hard`, porque de esta forma hago un reset head~1 más restore, que me permite tanto deshacer el último 
commit como los cambios hechos en el Working Copy, moviendo *HEAD* al commit especificado.

- **¿Qué comando o comandos usaste en el paso 12? ¿Por qué?**
`git reflog`, para poder mirar los movimientos de *HEAD* y poder tener acceso a lo eliminado, y`git reset 
--hard`, para volver al commit anterior

- **El merge del paso 13, ¿causó algún conflicto? ¿por qué?**
No, porque no había hecho más cambios al archivo desde la rama *main*.

- **El merge del paso 19, ¿causó algún conflicto? ¿por qué?**
Sí, porque modifiqué las mismas líneas del archivo en ambas ramas y además lo llevé al graph/repositorio

- **El merge del paso 21, ¿causó algún conflicto? ¿por qué?**
No, porque no había hecho más cambios al archivo desde la rama *main*.

- **¿Qué comando o comandos usaste en el paso 25?**
`git log --all --graph --decorate --oneline`

- **El merge del paso 26,  ¿podría ser fast-forward? ¿por qué?**
Sí, porque no se habían hecho cambios recientes al archivo en la rama *main*, así que *HEAD* podría haberse 
movido hasta el último commit donde se registró  el último cambio en la rama *title*

- **¿Qué comando o comandos usaste en el paso 27?**
`git reset Head~1`

- **¿Qué comando o comandos usaste en el paso 28?**
`git restore`

- **¿Qué comando o comandos usaste en el paso 29?**
`git branch -D title`

- **¿Qué comando o comandos usaste en el paso 30?**
`git reflog` y `git reset --hard commitDondeHiceElMerge`

- **¿Qué comando o comandos usaste en el paso 31?**
`git reset --hard primerCommitHecho`

- **¿Qué comando o comandos usaste en el paso 33?**
`git reset --hard 'commitDondeCreéTitle'`
