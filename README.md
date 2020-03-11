# Guía Repositorios Git Grupo Halley

Indicaciones sobre el uso de _git+GitHub_ para los proyectos del Grupo Halley de la Universidad Industrial de Santander.

> Guías rapidas de Git en los siguientes enlaces: 
> 
> - [https://rogerdudler.github.io/git-guide/index.es.html](https://rogerdudler.github.io/git-guide/index.es.html "Guía aspectos básicos git")
> - [https://wikis.fdi.ucm.es/ELP/Gu%C3%ADa_r%C3%A1pida_de_Github](https://wikis.fdi.ucm.es/ELP/Gu%C3%ADa_r%C3%A1pida_de_Github "Guía rapida Git")

## Repositorios Git

Se crearán repositorios independientes y se vincularán al proyecto en _GitHub_. A cada repositorio se agregará como colaborador al usuario [nunezluis](https://github.com/nunezluis "GutHub Luis Núñez").

Se espera tener repositorios para los siguientes productos:

- Propuesta de tesis.
- Documento final de tesis.
- Presentaciones a eventos.
- Códigos computacionales.

> Olvidarse de las practicas tipo programa-V1.py, programa-V2.py, programa-V3.py. El control de esos cambios y el mantener versiones anteriores se realiza mediante **commits**, para más información remitirse a las guiás _git_.

### Documentación

_Git + GitHub_ son herramientas poderosas para la gestión de sus proyectos, también para la preservación de los productos generados en el desarrollo de los mismos, sin embargo, debemos garantizar el entendimiento de los productos generados. 
Para dar unas condiciones mínimas de entendimiento, los repositorios deben tener un archivo tipo **README**, debe contar también, con archivos (especialmente los scripts) cuidadosamente documentados.

Algunas recomendaciones a continuación:

- Archivo README
    + Breve descripción del proyecto.
    + Instrucciones de uso/instalación.
    + Un corto ejemplo de uso.
- Scripts
    + Elegir convenciones y apegarse a ellas. Nombres para archivos, funciones, variables. Estrucutura de los archivos.
    + Describir claramente el objetivo y acciones para cada una de las secciones del script.
- Definir una licencia para los productos (para trabajos derivados es importante que las licencias de las fuentes y los productos nuevos sean compatibles).
- Dar credito a autores de trabajos no propios
- Agregar información de contacto.
- Para los notebooks tipo _Jupyter_ (La X Maravilla del mundo) usar los bloques en _Markdown_ para documentar y dar estructura el documento.

> A modo de resumen se espera que la documentación responda a las siguientes preguntas:
> 1. ¿Qué hace el código?
> 2. ¿Cómo lo hace?
> 3. ¿Cómo se usa?

> Guía rápida de _Markdown_ en [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet")

## Proyectos en GitHub

Para cada proyecto de tesis (o proyecto halley) se creará un proyecto en _GitHub_, cuyo nombre seguirá el formato **tesisJPerez** (Para la **tesis** de **J**osé **Perez**). Al proyecto se agregará como colaborador con rol de **Administrador** al usuario [nunezluis](https://github.com/nunezluis "GutHub Luis Núñez").

> Asegurarse de la asignación del rol administrador.

El proyecto se puede crea desde el siguiente enlace [https://github.com/new/project](https://github.com/new/project "Nuevo proyecto GitHub") o desde la esquina superior derecha en el icono **+** al lado de su foto de perfil. El proyecto **no** se crea dentro de un repositorio, de este manera el proyecto queda asociado únicamente al repositorio donde fue creado.

Se deben vincular al proyecto **todos** los repositorios pertinentes.

### Milestones & Issues

Una vez definidos objetivos y actividades del proyecto, estos se traduciran en **milestones** e **issues** en _GitHub_ de acuerdo a:

- Milestones: Conjunto de issues que permiten cumplir un objetivo o hito dentro del proyecto.
- Issues: tareas o mejoras específicas a realizar dentro del proyecto.

Es importante definir fechas en los **milestones**.

### Project Board

En el tablero del proyecto se crearán cuatro columnas de la siguiente manera:

1. Backlog: Pila de actividades, objetivos y descripción en resumen del proyecto.
2. To Do: Actividades (Issues) por hacer.
3. In Progress: Actividades (Issues) realizandose en el momento.
4. Done: Actividades (Issues) realizadas.

> Para todo lo demás existen los servicios de busqueda, foros y páginas de ayuda, especialmente la de [ayuda de _GitHub_](https://help.github.com/es "Ayuda de GitHub"). 

## Gestión de Datos

_Git_ **NO** esta diseñada para la gestión de datos y aunque lo permita, no es una forma eficiente ni práctica. Teniendo en cuenta esto, la gestión de los conjuntos de datos relacionados a los proyectos halley se hará con el servicio de repositorio [Zenodo](https://zenodo.org/ "Zenodo").

> Si el total del tamaño de los datos usados en el proyecto no es mayor a 50 MB se pueden gestionar desde _Git_.

### Zenodo

_Zenodo_ es un sistema de repositorio de datos de proposito general desarrollado en el marco de la estrategia OpenAIRE y mantenido por el CERN. Este sistema permite el deposito una gran variedad de contenidos digitales. A cada deposito en _Zenodo_ se le asigna un _Identificador Digital Persitente_ (PID) el cual permite, entre otros, referecniar de manera ágil y eficiente los contenidos digitales.

Los conjuntos de datos publicados asignados deberán ser asginados a la comunidad [halleyuis](https://zenodo.org/communities/halleyuis?page=1&size=20 "Halley UIS Zenodo").

> En este apartado se esperan nuevas indicaciones, las cuales se estarán anunciando. :)

