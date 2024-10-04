
# :blush: Tarea repositorio GitHub :blush: #

<br></br>

## :relieved: Comprobar versión de git, el usuario, email y clonar repositoio :relieved: ##

```
PS C:\Users\Alexa> git --version
git version 2.46.2.windows.1
PS C:\Users\Alexa> git config --global user.name
alexfdb
PS C:\Users\Alexa> git config --global user.email
alexanderfaustinodiazbautista@gmail.com
PS C:\Users\Alexa> git clone https://github.com/alexfdb/repositoio-ejercicio-1
Cloning into 'repositoio-ejercicio-1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.
```

<br></br>

## :flushed: Modificar el archivo README.md :flushed: ##

```
PS C:\Users\Alexa> cd .\repositoio-ejercicio-1\
PS C:\Users\Alexa\repositoio-ejercicio-1> git add .\README.md
PS C:\Users\Alexa\repositoio-ejercicio-1> git commit -m "Añadir título y descripción al README"
[main 361a868] Añadir título y descripción al README
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\Users\Alexa\repositoio-ejercicio-1> git push origin main
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 373 bytes | 373.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/alexfdb/repositoio-ejercicio-1
   655a35b..361a868  main -> main
```

<br></br>

## :grin: Actualizar en local, añadir nuevos cambios y subirlos a GitHub :grin: ##

```
PS C:\Users\Alexa\repositoio-ejercicio-1> git pull origin main
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 1.01 KiB | 128.00 KiB/s, done.
From https://github.com/alexfdb/repositoio-ejercicio-1
 * branch            main       -> FETCH_HEAD
   361a868..86bb62e  main       -> origin/main
Updating 361a868..86bb62e
Fast-forward
 README.md | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\Users\Alexa\repositoio-ejercicio-1> git add .\README.md
PS C:\Users\Alexa\repositoio-ejercicio-1> git commit -m "Añadir última línea al README desde local"
[main 73d7ac1] Añadir última línea al README desde local
 1 file changed, 1 insertion(+)
PS C:\Users\Alexa\repositoio-ejercicio-1> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 363 bytes | 363.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/alexfdb/repositoio-ejercicio-1
   86bb62e..73d7ac1  main -> main
```

*No se como crear la carpeta para añadirte el pantallazo de los commits* :sweat: <br>
*Y tuve problemas con la MV por eso el terminal es de mi maravilloso win 11* :heart:
