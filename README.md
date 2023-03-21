# Comandos utilizados en el juego learning branching git

## Principal

- git commit
- git checkout bugFix
- git checkout -b bugfix
- git branch bugFix
- git checkout main
- git merge bugFix
- git rebase main
- git checkout c4
- git checkout bugFix^
- git brah -f main c6
- git checkout HEAD~1
- git branch -f bugFix HEAD~1
- git reset HEAD~1
- git checkout pushed
- git revert HEAD
- git cherry-pick c3
- git cherry-pick c4 c7
- git rebase -i HEAD~3
- git rebase -i HEAD~4
- git rebase -i main
- git brach -f main bugFix
- git rebase -i HEAD~2
- git commit --amend
- git rebase caption main
- git cherry-pick c2 c3
- git tang v1 side^ 
- git tag v0 main~2
- git checkout v1
- git descrbe main
- git describe side
- git describe bugFix
- git rebase main bugFix
- git rebase bugFix side
- git rebase side another
- git branch bugwork main^^2^
- git checkout one
- git cherry-pink c4 c3 c2
- git checkout two
- git cherry-pink c5 c4 c3 c2
- git bracnh -f thre c2
- git clone
- git checkout o/main
- git pull
- git fetch
- git push
- git fackeTeamwork
- git pull --rebase
- git reset --hard o/main
- git checkout -b feacture c2
- git push origin feacture

## Remotes

- git rebase side1 side2
- git rebase side2 side3
- git rebase side3 main
- git merge side1
- git merge side2
- git merge side3
- git push origin main
- git push origin foo
- git push origin main~:foo
- git push origin foo:main
- git fetch origin main~1:foo
- git fetch origin foo:main
- git checkout foo
- git merge main
- git push origin :foo
- git fetch origin :bar
- git fetch origin bar:foo
- git origin main:side

## Funcion de cada uno de estos comandos

### Principales

- git commit: Este comando guarda los cambios realizados en el repositorio en un nuevo commit.
- git checkout bugFix: Este comando cambia a la rama 'bugFix'.
- git checkout -b bugfix: Este comando crea una nueva rama llamada 'bugfix' y cambia a ella.
- git branch bugFix: Este comando crea una nueva rama llamada 'bugFix'.
- git checkout main: Este comando cambia a la rama 'main'.
- git merge bugFix: Este comando fusiona la rama 'bugFix' con la rama actual.
- git rebase main: Este comando aplica los cambios de la rama 'main' a la rama actual.
- git checkout c4: Este comando cambia al commit identificado por el hash 'c4'.
- git checkout bugFix^: Este comando cambia al commit padre del último commit en la rama 'bugFix'.
- git branch -f main c6: Este comando establece la rama 'main' en el commit identificado por el hash 'c6'.
- git checkout HEAD~1: Este comando cambia al commit padre del último commit en la rama actual.
- git branch -f bugFix HEAD~1: Este comando establece la rama 'bugFix' en el commit padre del último commit en la rama actual.
- git reset HEAD~1: Este comando elimina el último commit y revierte los cambios en el repositorio.
- git checkout pushed: Este comando cambia a la rama 'pushed'.
- git revert HEAD: Este comando crea un nuevo commit que revierte los cambios del último commit.
- git cherry-pick c3: Este comando aplica los cambios del commit identificado por el hash 'c3' al commit actual.
- git cherry-pick c4 c7: Este comando aplica los cambios de los commits identificados por los hash 'c4' y 'c7' al commit actual.
- git rebase -i HEAD~3: Este comando inicia un proceso interactivo para fusionar los últimos tres commits en uno solo.
- git rebase -i HEAD~4: Este comando inicia un proceso interactivo para fusionar los últimos cuatro commits en uno solo.
- git rebase -i main: Este comando inicia un proceso interactivo para fusionar los commits de la rama actual con los de la rama 'main'.
- git branch -f main bugFix: Este comando establece la rama 'main' en el mismo commit que la rama 'bugFix'.
- git rebase -i HEAD~2: Este comando inicia un proceso interactivo para fusionar los últimos dos commits en uno solo y reordenarlos.
- git commit --amend: Este comando modifica el último commit con nuevos cambios.
- git rebase caption main: Este comando fusiona los cambios de la rama 'caption' con los de la rama 'main'.
- git cherry-pick c2 c3: Este comando aplica los cambios de los commits identificados por los hash 'c2' y 'c3' al commit actual.
- git tang v1 side^: Este comando crea una nueva rama llamada 'v1' a partir del commit padre del último commit en la rama 'side'.
- git tag v0 main~2: Crea una etiqueta con el nombre "v0" en el commit que se encuentra dos padres por encima del commit "main".
- git checkout v1: Cambia al commit referenciado por la etiqueta "v1".
- git describe main: Muestra una descripción corta del commit más reciente en la rama "main", incluyendo el número de commits desde ese punto y el hash del commit.
- git describe side: Muestra una descripción corta del commit más reciente en la rama "side", incluyendo el número de commits desde ese punto y el hash del commit.
- git describe bugFix: Muestra una descripción corta del commit más reciente en la rama "bugFix", incluyendo el número de commits desde ese punto y el hash del commit.
- git rebase main bugFix: Reaplica los cambios de la rama "bugFix" sobre la rama "main".
- git rebase bugFix side: Reaplica los cambios de la rama "side" sobre la rama "bugFix".
- git rebase side another: Reaplica los cambios de la rama "another" sobre la rama "side".
- git branch bugwork main^^2^: Crea una nueva rama llamada "bugwork" que apunta al commit dos padres por encima del segundo ancestro del commit actual de la rama "main".
- git checkout one: Cambia a la rama "one".
- git cherry-pick c4 c3 c2: Aplica los cambios de los commits "c4", "c3" y "c2" al commit actual.
- git checkout two: Cambia a la rama "two".
- git cherry-pick c5 c4 c3 c2: Aplica los cambios de los commits "c5", "c4", "c3" y "c2" al commit actual.
- git branch -f thre c2: Mueve la rama "thre" para que apunte al commit "c2".
- git clone: Crea una copia local de un repositorio remoto.
- git checkout o/main: Cambia a la rama "main" del repositorio remoto llamado "o".
- git pull: Obtiene y fusiona los cambios del repositorio remoto en la rama actual.
- git fetch: Obtiene los cambios del repositorio remoto sin fusionarlos.
- git push: Envía los cambios locales al repositorio remoto.
- git fakeTeamwork: Ejecuta un script para simular la colaboración de varios desarrolladores en un proyecto.
- git pull --rebase: Obtiene los cambios del repositorio remoto y los reaplica sobre la rama actual.
- git reset --hard o/main: Restablece el estado del repositorio local al estado del repositorio remoto llamado "o/main".
- git checkout -b feacture c2: Crea una nueva rama llamada "feacture" que apunta al commit "c2" y cambia a esa rama.
- git push origin feacture: Envía los cambios locales en la rama "feacture" al repositorio remoto llamado "origin".

### Remotes

- git rebase side1 side2: Rebase los cambios en side1 ramificar side2.
- git rebase side2 side3: Rebase los cambios en side2 ramificar side3.
- git rebase side3 main: Rebase los cambios en side3 ramificar main rama.
- git merge side1: Combinar los cambios en side1 ramificar en la rama actual.
- git merge side2: Combinar los cambios en side2 ramificar en la rama actual.
- git merge side3: Combinar los cambios en side3 ramificar en la rama actual.
- git push origin main: Empuje los cambios en el local main ramificación al control remoto origin/main rama.
- git push origin foo: Empuje los cambios en el local foo ramificación al control remoto origin/foo rama.
- git push origin main~:foo: Eliminar el foo ramificación en el control remoto origin repositorio.
- git push origin foo:main: Empuje los cambios en el local foo ramificación al control remoto main rama.
- git fetch origin main~1:foo: Trae el main ramificación en el control remoto origin repositorio y crear una nueva sucursal local foo que apunta a la confirmación un paso antes de la punta de origin/main.
- git fetch origin foo:main: Trae el foo ramificación en el control remoto origin repositorio y crear una nueva sucursal local main que apunta a la misma confirmación que origin/foo.
- git checkout foo: Cambiar al local foo rama.
- git merge main: Combinar los cambios en el main ramificar en la rama actual.
- git push origin :foo: Eliminar el foo ramificación en el control remoto origin repositorio.
- git fetch origin :bar: Eliminar el bar ramificación en el repositorio local y en el control remoto origin repositorio.
- git fetch origin bar:foo: Trae el bar ramificación en el control remoto origin repositorio y crear una nueva sucursal local foo que apunta a la misma confirmación que origin/bar.
- git origin main:side: Empuje los cambios en el control remoto main ramificación al control remoto side rama.


## Nombre y Matricula

Nombre: Esteban Pacheco

Matricula: 2021-1076
