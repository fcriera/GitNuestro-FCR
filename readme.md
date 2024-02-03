11. git reset --hard HEAD~1. Uso este código porque reset --hard me modifica el working copy según a donde indico que mi HEAD retorne (~1,2... cuantos commits le idique que regrese como máx al incio)
12. git reset --hard (commit anterior al paso 11): Lo uso poruqr al hacer hard modifica el working copy y con el identificador de commit me dirijo al commit que quiero recuperar
13. No, ya que los archivos son idénticos. Los cambios de *,'' no son detectados como conflicto al hacer el merge.
19. Sí causo conflicto ya que los archivos tienen diferentes caracteres que al querer unir los dos archivos tuve que indicar al programa que cambios me quiero quedar
21. No causo conflicto, de hecho me crea un merge ff.
25. git config alias.graph "log --graph --decorate --pretty=oneline"
    git graph.... (graph es el nombre que uso para este comando que me genera un gráfico decorado, y resumido)
26. Sí, porque si hago un merge ff el head se podía crear continuando la rama title
27. git reset
28. git reset --hard (identificador del commit donde se hizo el merge)
29. git branch -D title
30. git checkout (commit donde añadí el título)
git branch nam
git checkout main
git merge nam
git branch -D nam
32. git checkout (identificador del commit inicial)
33. git checkout main