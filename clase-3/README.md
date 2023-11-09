# Git & GitHub
**Git** es un sistema que nos permite controlar los cambios o versiones de nuestro codigo. <br/>
Mientras **Github** por su parte es un sitio web que nos permite almacenar o guardar los proyectos donde hemos usado Git.<br/>
Así como Github existen otros sitios web que ofrecen servicios similares como son [Gitlab](https://about.gitlab.com) y [Bitbucket](https://bitbucket.org)

## INICIANDO CON GIT
Existen dos formas de comenzar a trabajar con **Git**, una es creando un repositorio desde cero y la otra es clonando un repositorio que ya exista

* ### GIT DESDE CERO
  El comando que se requiere para esto es **git init**, que como veras en la lista mas abajo, es el comando que inicializa un repositorio en tu directorio local.<br/>
  Estan simple como transcribir el comando en tu terminal de comandos y presionar Enter, con eso ya tienes un repositorio local y puedes comenzar a usar "nuestro flujo de trabajo"

* ### CLONANDO REPOSITORIO
  La otra forma de hacerlo es clonando un repositorio almacenado en la nube, usando el comando **git clone**, esta es la forma mas común y con la que trabajaran mas a lo largo de su carrera como programadores.
  Tiene la siguiente sintaxis: **git clone https://github.com/usuario/nombre-del-repositorio.git [DESTINO]** <br/>
  Donde "[DESTINO]" puede ser el nombre de alguna carpeta donde se guardara el contenido del repositori o un "punto", si ese es el caso le estamos indicando que guarde los archivos en la carpteta donde nos encontramos

## NUESTRO FLUJO DE TRABAJO
* git add .
* git commit -m "mensaje"
* git pull
* git push


## PRINCIPALES COMANDOS GIT
* git init: Inicializa un nuevo repositorio Git en un directorio local.

* git add .: Añade todos los cambios realizados en los archivos al área de preparación.

* git branch: Lista, crea y elimina ramas en el repositorio.

* git checkout: Cambia a una rama específica en el repositorio.

* git status: Muestra el estado de los archivos en tu directorio de trabajo y en el área de preparación.

* git commit -m "mensaje": Crea un nuevo commit que almacena una instantánea de los archivos en el área de preparación junto con un mensaje descriptivo.

* git pull: Obtiene los cambios más recientes del repositorio remoto y los fusiona en tu rama local.

* git push: Envía tus commits locales al repositorio remoto para compartir tus cambios con otros colaboradores.

* git clone : Clona un repositorio Git existente desde una ubicación remota a tu máquina local.
