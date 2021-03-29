# Clase 3

## Git

Nos permite tener un backup de nuestros archivos, y compartir nuestro trabajo con los demás colaboradores de nuestro equipo.

Es un **software de control de versiones**.

**Repositorio local** -> Es el que tiene todos los archivos (que hayas guardado en él) en la computadora.

**Commits** -> Son los paquetes que nos van a permitir ir haciendo un seguimiento de los cambios que vamos realizando, dado que cada uno de ellos tiene una timestamp y un autor.

- git init
- git config user.name "nombre de usuario"
- git config user.email "nombreUsuario@email.com" 
- git remote add origin https://github.com/DH/RepoRemoto
- git add .
- git status // seguimiento del estado de los archivos
- git commit -m "mensaje" // comitea los cambios hechos
- git log // muestra un registro de los cambios, historial de commits