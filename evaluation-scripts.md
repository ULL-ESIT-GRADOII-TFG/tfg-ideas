Siguiendo la metodologías de los submódulos y el `git submodule foreach `
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

### Véase También

* [How can I automate the grading of programming assignments?](https://cseducators.stackexchange.com/questions/1205/how-can-i-automate-the-grading-of-programming-assignments) en [https://cseducators.stackexchange.com](https://cseducators.stackexchange.com)
* [What tools do you use for automated grading of assignments that involve programming?](https://www.researchgate.net/post/What_tools_do_you_use_for_automated_grading_of_assignments_that_involve_programming) en https://www.researchgate.net
* [GitHub README Analyzer
An experiment to algorithmically improve your GitHub README](https://demos.algorithmia.com/github-readme-analyzer/)
*  [codio](https://codio.com/features/infrastructure/)
    - [Grading with Codio](https://vimeo.com/214168086)
