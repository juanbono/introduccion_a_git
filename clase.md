# Clase de introduccion a sistemas de control de versiones (GIT)

## Que es?

Un sistema de control de versiones (abreviado VCS en ingles) sirve para gestionar nuestro proyecto de software
a lo largo de su ciclo de vida. Hace mas eficiente la colaboracion y nos permite administrar cambios y versiones de manera eficaz.

## Que es un proyecto de software?

Conjunto de documentos, diagramas, assets (imagenes, iconos, etc), scripts y codigo fuente que conforman un sistema.

## Por que necesito un VCS?
Sin el, caemos en:
- Versionado manual: `proyecto_final.zip`, `proyecto_final_v2.zip`, `proyecto_AHORA_SI_final.zip`
- Dificultades para colaborar entre muchas personas
- Perdida de historial y de trabajo valioso
- Resistencia al cambio (Miedo a "romper" lo que ya funciona)

Todo esto resulta en malas practicas y aumenta la probabilidad de errores --> Aumenta el costo del proyecto














## Qué es un VCS?
    *   Un sistema que registra los cambios realizados en un archivo o conjunto de archivos a lo largo del tiempo.
    *   Permite recuperar versiones específicas (si algo sale mal o necesitamos analizarlo).
    *   Analogía: Historial de cambios de Google Docs/Word
    *   Colaboración Eficiente: Múltiples personas trabajando en el mismo proyecto sin pisarse.
    *   Experimentación Sin Miedo (Branches): Probar ideas nuevas sin afectar la versión principal.
    *   Copias de Seguridad: El repositorio remoto actúa como backup

En resumen, permite escalar el desarrollo de proyectos de software al dar una herramienta para gestionar su evolucion de manera segura.











## GIT, el VCS mas utilizado
- Creado en 1995 por Linus Torvalds (creador del sistema operativo Linux)
- Es el mas utilizado a nivel profesional
- Facil de usar
- Fundamental para el desarrollo de software open-source
- Posee una gran cantidad de material para aprenderlo
- Pagina: https://git-scm.com/

## Conceptos clave

- **Repositorio (repo)**: Directorio donde se almacena el proyecto. 
- **Repositorio Local**: La copia del proyecto que tenemos en nuestra computadora.
- **Repositorio Remoto**: Copia del proyecto en un servidor/proveedor de Git (puede ser GitHub, GitLab, BitBucket, etc)
- **Branch**: Version del proyecto sobre la que estoy trabajando. 
- **Historial**: Conjunto de commits ordenados
- **Branch master** o **Branch main**: Version canonica u oficial del proyecto. 

> Ver donde descargar GIT
> Ver como inicializar un proyecto













## Flujo normal de uso

1. Escribir/modificar/eliminar archivos del proyecto.
2. Preparar los cambios para ser subidos al repositorio remoto (commit)
3. Subir los cambios al repositorio remoto (push)

> Inicializar repositorio remoto y asociarlo al repositorio local
> Hacer cambios locales
> Mostrar cambios 
> Hacer add y commit de los cambios
> Hacer push del commit al repositorio remoto
> Ver cambios en el historial del repositorio remoto
> Ver historial de commits en el repositorio local (git log)


## Resumen de comandos

- git init: Inicializa el repositorio en el directorio en el que este ubicado
- git status: Permite ver los cambios realizados y que aun no fueron commiteados
- git add: Permite agregar un cambio al commit en preparacion
- git commit: sella un paquete de cambios
- git push: Envia al repositorio remoto todos los commits locales con el objetivo de sincronizarlo
- git log: Permite ver localmente el historial de commits

Intuicion: cuando usamos git, la evolucion de un proyecto de software queda plasmada en su historial de commits.

Puedo volver a un commit anterior para restaurar cambios
Puedo trabajar en paralelo en diferentes ramas
Puedo luego unificar estas ramas en un historial comun
