# Práctica del curso de **git**, **gitHub** y **Sourcetree**

<p>-¿Qué comando utilizaste en el paso 11? ¿Por qué?<br />
	<code>git reset -- hard HEAD~1</code> <br />
Utilice el comando con el modificador hard para asi perder tambien los cambios realizados en el working copy<br />

-¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?<br />
	<code>git reflog</code><br />
	<code>git reset -- hard 0b53258</code><br />	
Utilice el comando reflog para buscar el identificador donde estaba el ultimo commit, y con el comando reset -- hard 
y el indicador poder rehacer el último commit <br />

-El merge del paso 13, ¿Causó algun conflicto? ¿Por qué?<br />
No, no causo ningún conflicto porqué solo modificamos el archivo en una rama.<br />

-El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?<br />
Sí, por que hemos modificado el mismo archivo en las mismas líneas.<br />

-El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?<br />
No, por que no modificamos ninguna linea.

-¿Qué comando o comandos utilizaste en el paso 25?<br />
	<code>git log --graph --decorate --pretty=oneline<br />

-El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?<br />
No, por que habiamos creado un commit en cada rama.<br />

-¿Qué comando o comandos utilizaste en el paso 27?<br />
	<code>git reset HEAD~1</code><br />

-¿Qué comando o comandos utilizaste en el paso 28?<br />
	<code>git checkout -- git-nuestro.md</code><br />

-¿Qué comando o comandos utilizaste en el paso 29?<br />
	<code>git branch -D title</code><br />

-¿Qué comando o comandos utilizaste en el paso 30?<br />
	<code>git reflog</code><br />
	<code>git reset -- hard 3a272b4</code><br />

-¿Qué comando o comandos utilizaste en el paso 32?<br />
	<code>git reflog</code><br />
        <code>git reset -- hard 2c960d3</code><br />

-¿Qué comando o comandos utilizaste en el paso 33?<br />
	<code>git reflog</code><br />
        <code>git reset -- hard 9692d54</code><br />

