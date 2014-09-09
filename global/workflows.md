Workflows
=========

Aquí está el flujo de trabajo para la planeación, seguimiento, desarrollo y lanzamiento de los productos.

# Planeación y seguimiento

* Cada reunión de los martes es para conocer los features que se pusieron a producción y los nuevos features de la próxima versión.
* Cada reunión de los jueves es para conocer los avances en el sprint.
* Cada sprint abierto debe generar un release.
* Los sprints son de una semana, abren el martes y cierran el lunes.
* Cada producto tiene la obligación de lanzar una actualización del producto hasta con 2 semanas entre un lanzamiento y otro.
* Los números de versión son de 3 digitos (Por ejemplo: 0.0.2), donde el primer dígito establece una versión del producto, el segundo una actualización mayor y el último una actualización menor.
* Los colaboradores tienen la obligación de cumplir al menos con un issue por día.
* Los funcionalidades deben ser bien divididos en issues que no generen que los colaboradores demoren más de 24 horas desarrollando determinada funcionalidad.

# Proceso de desarrollo

* Cada proyecto debe tener un repositorio en http://bitbucket.org.
* Cada proyecto debe tener un responsable.
* Cada proyecto debe tener documentación, sobre los componentes principales del proyecto, el objetivo, la estructura de archivos, detalles de implementación, guias de estilo, roadmap y como correr para desarrollo.
* Cada proyecto debe tener su control de issues en http://bitbucketcards.com.
* La rama base de cada proyecto debe llamarse *Master*.
* De la rama base deben generarse ramas con el número de versión en desarrollo (Por ejemplo: v0.0.7).
* De cada versión en desarrollo, por cada issue debe generarse una rama, la cual tiene el issue desarrollado (Por ejemplo: [projectName]/[userName]/[issueNumber]-[issueDescription]).
* Por cada issue debe generarse un Pull Request.
* El Pull Request debe ser validado y aprobado por el responsable del proyecto.
* Solo el administrador puede aceptar y mezclar los pull request.

# Proceso de puesta a producción

* Cada proyecto debe contener una carpeta server, donde el responsable a colocado scripts para la puesta en producción del proyecto.
* Cada proyecto debe contener documentación sobre como poner manualmente a producción el proyecto.
* Solo Julián puede poner en producción las ramas master de los proyectos.
* Josue Camara tiene la posibilidad de poner en producción las ramas master de los proyectos, con previa autorización de Julián.

# Libre transito

* Los responsables de proyecto en caso de quedar sin issues pueden colaborar en otro proyecto.
* Para la colaboración en un proyecto, es necesario solicitar aprobación y actualización del lider de proyecto para colaborar.
* Al momento de recibir un issue en el proyecto del cual eres responsable, debes concluír el issue del proyecto en el que colaboras y posteriormente puedes moverte a tu proyecto.
