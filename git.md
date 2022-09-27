# Git / GihHub

## Configurar usuario y correo en local

1. Establecer la identidad del usuario de forma global: `git config --global user.name "knnv-ar"`
2. Para verificar la identidad del usuario asignado al proyecto actual: `git config user.name`
3. Establecer el correo del usuario de forma global: `git config --global user.email "knvv.ar@gmail.com"`
4. Para verificar el correo del usuario asignado al proyecto actual: `git config user.email`

## Crear un proyecto nuevo en local y vincular su repositorio en Github

1. Ejecutar Git Bash.
2. Ir hasta la carpeta del proyecto.
3. Inicializar el control de versionado del proyecto: `git init`

## Creo un repositorio en GitHub y lo clono en local

1. Crear un nuevo repositorio en Github.
2. Copiar la **URL** con formato git https.
3. Vincular el proyecto actual (en la carpeta que esté parado) con su repositorio en GitHub: `git remote add origin https://github.com/knnv-ar/prueba-node.git`
4. Para verificar que la conexión se realizó de forma exitosa: `git remote -v`

## Documentación

https://learngitbranching.js.org/?locale=es_ES

https://gitexplorer.com/
