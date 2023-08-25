# git_h-8
<h3> H-8 (VOLVER A UN COMMIT ANTERIOR)👀👀👀 </h3>

1.Crear un nuevo repositorio en github nombre: git_h-8

2.Crear un repositorio local

>git init

3.Registrar el repositorio remoto con tú repositorio local

>git remote add origin (pegar_la_ruta_del_repositorio_local)

4.Verificamos la ruta remota

>git remote -v

5.Crea 5 archivos notas_1.txt, notas_2.txt etc... y por cada archivo emites un commit y su push correspondiente por cada commit

>touch nota_1.txt - commit -m "feat nota 1" y push

> touch nota_2.txt - commit -m "feat nota 2"  y push

> touch nota_3.txt - commit -m "feat nota 3"  y push

> touch nota_4.txt - commit -m "feat nota 4"  y push

> touch nota_5.txt - commit -m "feat nota 5"  y push


6.Ahora vamos a regresar del actual commit, al commit anterior, es decir del ultimo commit que tiene contiene los "5 archivos", al commit pasado que contiene solamente los "4 archivos"

>git revert HEAD~1 ( este metodo no me gusto

+ Otra alternativa al mismo resultado

git revet código_del_actual_commit  código_del_commit_pasado ( este no lo realice)

7.Luego si existe un conflicto solo seleccionamos lo que necesitamos, teniendo ya todo listo, se continua con el revert

>git revert --continue ( este comando no me funciono)

<h3> Nota Importante</h3>

> Si quiero revertir un commit lo mejor para mi es hacer un git log y me aparecen todos los commits y de ahi escojo cual quiero eliminar entonces seria algo

> git revert ( se pegan todos los caracteres del commit a revertir)

8. Para subir el commit modificado

> git commit --amend -m "feat: volvemos al commit anterior"

9.Revisamos el proyecto para confirmar y podemos seguir creando cosas en nuestro proyecto.

<h3> END
👏👏👏</h3>
