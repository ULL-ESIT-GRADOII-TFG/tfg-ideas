Siguiendo la metodologías de los submódulos y el `git submodule foraeach `
escribir familia de scripts para asistir en las tareas de evaluación

### Grade-node

* [https://www.npmjs.com/package/ghedsh-grade-node](https://www.npmjs.com/package/ghedsh-grade-node)

* Restringir la acción del `foreach` con una regexp que actuen sobre `$name` o `$path` cob  los que casan,
    - $name is the name of the relevant submodule section in .gitmodules, $path is the name of the submodule directory relative to the superproject.
    - `grade-node -t /teacher/tests/dir -o output.md --name /regexp/`
* Restringir la acción del `foreach` con una regexp que actuen sobre `$name` o `$path` cob  los que NO CASAN,
    - `grade-node -t /teacher/tests/dir -o output.md --noname /regexp/`
   
* Soporte para Travis, CircleCI, etc. 
    - Se copian los tests del profesor y se hace un push
    - Se usa la  API de Travis, CircleCI, etc. para obtener los resultados ?
    - Se generan las incidencias para los alus

