# Ejemplo HTML
## Pruebas de agregado a gitHUB

! y enter para crear una estructura basica de html


Commit ver historico:


´git log --online´

En cada commit tenemos el ID
Y en la siguiente instruccion podemos ir al momento de ese commit con todos los cambios0
´git checkout ID´

Para volver 
´git checkout main´


Para retroceder en el tiempo buscar el ID con el comando anterior y:
´git reset --hard ID´

Si nos hemos equivocado y queremos volver buscar el ID con:
´git reflog´ + ´git reset --hard ID´


Pero puede dar problemas con el repo de GitHUB si hay commits no actualizados entre local y gitHUB
Para ello se elimine un commit en particular 
´git revert ID ´


Mejor usar branch

´git branch 01-rama´ para crear una rama

Merge 

Nos posicionamos en la rama que va a recibir la rama o main
´git merge NombreRAMA´
