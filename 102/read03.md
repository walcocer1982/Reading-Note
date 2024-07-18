# Control de Versiones

El control de versiones es una herramienta que facilita la gestión de múltiples proyectos o versiones de un archivo al registrar los cambios efectuados. Esto permite mantener un seguimiento eficiente y facilita la corrección y modificación de errores.

## ¿Qué significa "clone" en Git?

El comando `git clone` copia todas las versiones de un archivo específico. Al ejecutar `git clone urlDelRepositorio` en Git bash, se crea un directorio en el área de trabajo que contiene todas las versiones del repositorio, incluyendo la más reciente sobre la cual se está trabajando.

## Comandos básicos en Git

### Rastrear y preparar archivos para commit

El comando `git add .` se emplea para buscar en el directorio actual, seleccionando todos los archivos modificados y marcándolos para ser incluidos en el próximo commit.

### Crear una instantánea de los cambios

Para registrar oficialmente los cambios en el repositorio, se utiliza `git commit -m "Descripción breve de los cambios"`, lo cual permite guardar una instantánea de los cambios realizados con una descripción asociada.

### Enviar cambios a GitHub

Para subir los cambios realizados localmente a un repositorio remoto en GitHub, se utiliza `git push origin main`. Este comando sincroniza el repositorio local con el remoto, enviando todas las modificaciones.
