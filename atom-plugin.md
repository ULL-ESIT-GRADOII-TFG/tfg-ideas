## Plugin for GH Classroom

Write a plugin for the Atom editor using Electron.

* The plugin will give support similar to the GitHub plugin but oriented to organizations and teachers.
* It will be similar to Berkan's tool and to classroom assistant

Yo empezaría haciendo el tutorial

* https://blog.github.com/2016-08-19-building-your-first-atom-plugin/


Aquí hay otro tutorial:

* https://blog.eleven-labs.com/en/create-atom-package/


Aquí hay otro:

* https://www.sitepoint.com/write-atom-packages-using-vanilla-javascript/

En este vídeo explico como se usa Git y GitHub desde Atom:

*                      https://youtu.be/kFtGxyyLRTc

esto te da una idea de como deberían ser las funcionalidades del plugin que se haga en el  TFG. La charla se corresponde con el tutorial:

* https://flight-manual.atom.io/using-atom/sections/github-package/


Los fuentes del paquete github para atom parecen estar aquí:

* https://github.com/atom/github

Los fuentes de open-on-github:

* https://github.com/atom/open-on-github


Creo que deberíamos empezar con un objetivo modesto, como simplemente mostrar en una ventana la lista de las organizaciones GitHub del usuario.

List of Atom plugins for GitHub functionalities:

* https://atom.io/packages/search?utf8=%E2%9C%93&q=github&commit=Search

## Plugin Find Project from GitHub

It will find the local path to a given github repo, for instance

```
ULL-ESIT-TFG/ghedsh
```

and will offer to the user to open the project.

It has an associated JSON file with the known relations:

```json
{
  "ULL-ESIT-TFG/ghedsh" : {
    "machine": "Darwin sanclemente-2.local",
    "path": "/Users/casiano/local/src/githubclassroom/clementeTFG/teachers_pet-terminal",
    "user": "casiano"
  },
  ...
}
```


Has commands as:

1. Save relation between repo and path
2. Open local repo ULL-ESIT-TFG/ghedsh

**Related Plugins:

* [recent-projects](https://atom.io/packages/recent-projects)


## Plugin for TOC

Update the plugin [markdown-toc](https://github.com/nok/markdown-toc)

## Plugin for GitBook

To give support for GitBook

* [atom-gitbook](https://github.com/cthos/atom-gitbook)

## Plugin for Moodle

It will create a navigation window to quickly go to

* Asignaturas
* Estudiantes
* Libro de Calificaciones
* Tareas

Posiblemente parsear ficheros HTML ya que no se dispone de servicio web
