![git comandos](https://raw.githubusercontent.com/sergiecode/git-comandos-importantes/master/1.jpg)

![git comandos2](https://raw.githubusercontent.com/sergiecode/git-comandos-importantes/master/2.jpg)

![git comandos 3](https://raw.githubusercontent.com/sergiecode/git-comandos-importantes/master/3.jpg)

![git comandos 4](https://raw.githubusercontent.com/sergiecode/git-comandos-importantes/master/4.jpg)


# GIT: Todos los Comandos que Debes Saber
## Introducción a Git

Git es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear y gestionar cambios en su código fuente a lo largo del tiempo. Facilita la colaboración en proyectos y la administración eficiente de flujos de trabajo. Aquí tienes algunos conceptos clave de Git:

-   **Repositorio**: Un repositorio Git almacena todo el historial de cambios y archivos de un proyecto.
-   **Rama (Branch)**: Una rama es una línea independiente de desarrollo. Puedes trabajar en diferentes características sin afectar la rama principal.
-   **Confirmar (Commit)**: Una confirmación registra un conjunto de cambios en el repositorio junto con un mensaje descriptivo.
-   **Fusionar (Merge)**: Fusiona los cambios de una rama en otra, combinando el historial y el contenido.
-   **Clonar (Clone)**: Clona un repositorio existente en tu máquina local.
-   **Empujar (Push)**: Envía tus cambios locales a un repositorio remoto.
-   **Tirar (Pull)**: Obtiene los cambios remotos y los fusiona en tu rama local.

## Configuración Inicial

Antes de comenzar, configura tu identidad en Git:

```
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

## Creación y Clonación de Repositorios

### Crear un Nuevo Repositorio

1.  Inicializa un nuevo repositorio:

`git init` 

### Clonar un Repositorio Existente

1.  Clona un repositorio existente:

`git clone <URL_del_repositorio>` 

## Trabajando con Ramas

1.  Crear una nueva rama y cambiar a ella:

`git checkout -b nombre_de_la_rama` 

2.  Cambiar a una rama existente:

`git checkout nombre_de_la_rama` 

3.  Listar todas las ramas:

`git branch` 

## Realizar Cambios

1.  Ver el estado de los archivos modificados:

`git status` 

2.  Ver las diferencias entre los archivos modificados y la última confirmación:

`git diff` 

3.  Agregar archivos modificados para la próxima confirmación:

`git add nombre_del_archivo` 

## Confirmar Cambios

1.  Confirmar los cambios con un mensaje descriptivo:

`git commit -m "Mensaje descriptivo"` 

## Sincronización y Colaboración

1.  Subir cambios locales a una rama remota:

`git push nombre_remoto nombre_rama` 

2.  Obtener cambios remotos y fusionarlos en tu rama local:

`git pull nombre_remoto nombre_rama` 

## Gestión de Conflictos

1.  Resolver conflictos entre fusiones:
    
    1.  Abre los archivos con conflictos.
    2.  Edita los conflictos.
    3.  Confirma los cambios.

## Herramientas Útiles

-   `git log`: Ver el historial de confirmaciones.
-   `git reset`: Deshacer cambios locales.
-   `git stash`: Guardar temporalmente cambios no confirmados.
-   `git merge`: Fusionar ramas.
-   `git remote`: Gestionar repositorios remotos.
