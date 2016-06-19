- ¿Qué comando utilizaste en el paso 11? ¿Por qué?<br>
git reset --hard HEAD~1<br>
Por que se ha solicitado deshacer el último commit modificando el working copy.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?<br>
git reset --hard 6d1b65c<br>
He utilizado el identificador del commit al que quiero regresar

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?<br>
La rama htmlify no ha sido creada aún

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?<br>
SI hubo conflictos, ya que las diferencias entre los archivos existen sobre la misma línea de texto.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?<br>
No hubo conflicto. Master ha absorbido los commits de styled.

- ¿Qué comando o comandos utilizaste en el paso 25?<br>
Con git reflog fue sencillo analizar el estado del grafo del repositorio.

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?<br>
Por que las ramas se encuentran en una lista.

- ¿Qué comando o comandos utilizaste en el paso 27?<br>
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?<br>
git checkout -- git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?<br>
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?<br>
Primero recupero la rama eliminada con git branch title 9a0d263<br>
Vuelvo a realizar el merge de master con title utilizando git merge --no-ff title

- ¿Qué comando o comandos usaste en el paso 32?<br>
git reset --hard bf91dc6

- ¿Qué comando o comandos usaste en el punto 33?<br>
git reset --hard 9a0d263
