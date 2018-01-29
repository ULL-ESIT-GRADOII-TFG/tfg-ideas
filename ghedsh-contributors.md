#### Metodología para crear una relacion ghedsh o extender información ghedsh desde Moodle

* Exporto el calificador desde Moodle a CSV, los campos que me interesan
* Uso [TableTool](https://github.com/jakob/TableTool) un editor de CSV par mac os muy útil
* Con el editor [TableTool](https://github.com/jakob/TableTool) elimino columnas, etc.
* Ahora puedo importar el fichero a ghedsh para 
  - Establecer una relacion ghedsh (`new relation file.csv`)
  - aumentar la información de la gente de la organizacióna (`new people info file.csv`)

#### Dudas

* ¿Que pasa con el hecho de que GitHub Classroom ahora añade a los alumnos como contributors y no como miembros de la organización? 
  - Véase el issue [[Feature request] Add students as organization member after accepting first assignment #1078](https://github.com/education/classroom/issues/1078)
* ¿Habrá que añadirle a ghedsh un comando `contributors` para encontrar los alumnos?
* ¿Automatizar el paso de contributor a members?
* [Converting an outside collaborator to an organization member](https://help.github.com/articles/converting-an-outside-collaborator-to-an-organization-member/)
* [Adding outside collaborators to repositories in your organization](https://help.github.com/articles/adding-outside-collaborators-to-repositories-in-your-organization/)
