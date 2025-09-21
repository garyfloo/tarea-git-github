# PRACTICA 1
## Parte 1

**¿Qué es Git y para qué se utiliza?**

El git es un sistema de control de versiones distribuidos.
Nos sirve para llevar registro de los cambios que se hacen en archivos de un proyecto.

**¿Qué diferencia hay entre Git y GitHub?**

>Git
Es la herramienta de control de versiones, corre localmente en la maquina guarda los cambios, permite hacer commits, ramas y mucho mas.
>GitHub
Permite alojar repositorios, colaborar con otras personas, hacer reviciones de codigo, ver historial de cambios, mostrar documentos, etc.

**Explica en tus palabras qué es un repositorio**

Es como un contenedor que incluye todos los archivos, carpetas, ramas. Es donde se guarda todo lo necesario para desarrollar un proyecto, puede ser local como remoto.

**Qué significa hacer un commit en Git?**

Es tomar captura de los archivos que estan preparados, registrados esos cambios en el historial del repositorio. 

**Investiga y explica brevemente los siguientes comandos de Git:**

1. git config --local user.name "<GitHub user name>"
Configura el nombre de usuario asociado a los commits solo para ese repositorio local. Sirve para identificar quién hizo los cambios.
2. git config --local user.email "<GitHub email>"
Configura el correo electrónico asociado a tus commits en ese repositorio, para que quien vea el historial sepa desde dónde viene el commit.
3. git init
Inicializa un repositorio Git nuevo en la carpeta actual. Crea la estructura necesaria (.git) para que Git pueda empezar a rastrear cambios.
4. git add
Prepara archivos o cambios para ser incluidos en el próximo commit. Los archivos que no están “staged” no formarán parte del commit.
5. git commit
Crea un  commit con los cambios que haya añadido con git add. Guarda esos cambios en el historial.
6. git push 
Envia los commits que tienes en un repositorio local hacia un reporitorio remoto. Hace que los cambios sean visibles para otros que esan ese repositorio remoto.
7. git clone
Copia un repositorio remoto a tu máquina local. Descarga todos los archivos, historial de cambios y ramas, para que puedas trabajar localmente.
8. git init --initial-branch-main
Inicia un repositorio Git como git init, pero especificando que la rama principal se llame “main” en lugar del nombre por defecto (que algunas versiones era “master” u otro). Es una forma más explícita de nombrar la rama inicial.
9. git remote add origin https://github.com/<user-name>/tarea-git-github.git
Establece un repositorio remoto llamado “origin” con la URL que se da. Se podria decir que le dices al Git local dónde es el repositorio remoto al que enviar (push) o desde el que obtener (pull) cambios.
10. git add .
Agrega todos los archivos del directorio actual y subdirectorios al área de preparado "staging area", para que estén listos para el próximo commit.
11. git commit -m "Initial commit"
Hace un commit con todos los cambios preparados (con git add) y da un mensaje descriptivo con la opción -m, en este caso “Initial commit” (“commit inicial”).
12. git push --set-upstream origin main
Empuja tus commits hacia el repositorio remoto llamado “origin” y además define que la rama local main rastree (track) la rama main del remoto. Es útil la primera vez que haces push, para que después solo con git push sepa hacia dónde enviar.

**Que es un archivo README.md y porque es importante**

Un README.md es un archivo de texto escrito en formato Markdown (.md) que normalmente está en la raíz de un repositorio. Suele contener:

- Una descripción del proyecto (qué hace, para qué sirve).

- Como instalarlo, cómo usarlo.

- Quiénes lo desarrollan, licencias, dependencias, etc.

> Es importante por

- Sirve como la “portada” del repositorio, lo primero que ven quienes lo visitan.

- Ayuda a que otras personas entiendan el propósito del proyecto sin tener que explorar todo el código.

- Facilita que otros lo usen, lo contribuyan, lo evalúen.

- Mejora la documentación general y la organización del proyecto.
