# Comandos Basicos En BASH
---
#### Manipulacion de directorios
- **cd:** Change Directory, como su nombre lo indica nos permite cambiarnos de directorio una vez le indiquemos la ruta a la cual nos queremos trasladar.
Las rutas se dividen en rutas relativas y rutas absolutas, algunos ejemplos son:

    Rutas relativas | Rutas absolutas
    --------------- | ---------------
    / | Home/Desktop/Folder
    ./ | Home/Pictures
    ../ | /Downloads
- **pwd:** Print Working Directory, se imprime en terminal la ruta del directorio         actual, se le conoce mejor como directorio de trabajo
- **mkdir:** Make Directory crea un directorio con el nombre que le indiquemos, por     ejemplo: 
**mkdir** _Proyecto_
- **rmdir:** Remove Directory sirve para eliminar directorios vacios
- **ls:** Permite visualizar los archivos de un directorio, para poder ver incluso      archivos es necesario agregar el argumento _-a_ 
---
#### Manipulacion de archivos
- **touch:** Permite crear archivos indicandole el nombre y su extension
- **cat:** Permite visualizar el contenido de un archivo en la terminal
- **echo:** Es un comando que imprime texto en consola, sin embargo, tambien es         utilizado para escribir sobre archivos. Haciendo uso del redireccionamiento (> o >>) podemos escribir contenido en los archivos (eliminando lo anterior) o agregar contenido a un archivo ya que tiene texto.
---
#### Comandos GIT
- Lo recomendable para empezar a trabajar en git es configurar el usuario y el email, para que git nos permita posteriormente realizar commits. Todos los comandos de git son antecedidos por la palabra git
- **git config:** git config permite configurar GIT, en este caso explicaremos como     agregar un nombre y un email para que GIT nos identifique.
    - _git config --global user.email **"correo@mail.com"**_
    - _git config --global user.name **"Marco Franco"**_
- **git add:** Permite agregar un archivo del **_working area_** al **_staging area_**, ya sea un archivo que haya sido modificado o que no se le este dando seguimiento "**_tracking_**"
- **git commit:** Los archivos que se encuentren en staging pasan al repositorio a traves de este comando. Normalmente va acomañado de un mensaje que describe el cambio que se ha realizado
- **git  log:** Muestra la lista de commits que se han hecho
- **git status:** Muestra el estado de GIT, es decir, si tenemos cambios en un archivo y este no ha sido agregado al staging area, si un archivo no esta llevando seguimiento, si no hay cambios.
    