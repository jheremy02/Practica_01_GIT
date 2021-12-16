#Practica 01

- **¿Qué comando utilizaste en el paso 11? ¿Por qué?**

git reset —hard  84dd8ba   : git reset me permite deshacer un commit brindadole como parametro el id del commit a donde quiero regresar , y el —hard fuerza a que se modifique mi working area.

- **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

git reflog : es como un log avanzado que me permite ver los cambios mas importantes hechos en mi repositorio.

git reset —hard d90c3c5 : ubico el id del commit que quiero restablecer y lo paso como parametro

- **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No causo conflicto porque fue un merge fast forward, la rama styled ya tenia los commit de la rama master.

- **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Si hubo conflictos porque en las 2 ramas habian modificaciones del mismo archivo git-nuestro.md en las mismas lineas.

- **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No hubo conflictos porque se ejecuto un merge fast forward, la rama master se trajo los commits de styled, apunta ahora  en el ultimo commit de styled pero master igual tiene acceso a su commit original donde estaba antes del merge ya que styled tambien tenia ese commit.

- **¿Qué comando o comandos utilizaste en el paso 25?**

git log --graph --pretty=oneline

- **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si podria , porque title ya tiene acceso a los mismo commit que master

- **¿Qué comando o comandos utilizaste en el paso 27?**

git reflog

git reset aef4b1e2af077b7baf05de1934930be7e4d0f4c4

- **¿Qué comando o comandos utilizaste en el paso 28?**

git restore git-nuestro.md

- **¿Qué comando o comandos utilizaste en el paso 29?**

git branch -D title

- **¿Qué comando o comandos utilizaste en el paso 30?**

git reflog

git reset --hard 80156e5038999c6b4c80448b3d7deec87a1f9588

- **¿Qué comando o comandos usaste en el paso 32?**

git log

git reset --hard 84dd8bad988d050074e50c1074aa39547da216ec

- **¿Qué comando o comandos usaste en el punto 33?**

git reflog

git reset --hard 6c6a53e
