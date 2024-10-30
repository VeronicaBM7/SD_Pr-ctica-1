# Introducción a Git

El programa 'HolaMundo.py' imprime un único mensaje. Esta practica tiene como objetivo familiarizarse con Git y GitHub. Git actúa como un sistema de control de versiones, el cual gestionia y raestrae cambios en el proyecto,
mientras GitHub áctua como el servidor para almacenar y compartir dicho proyecto. Esta herramienta es altamente utilizada en el desarrollo de software.

## Ejecucion del progrma **HolaMundo.py**
python HolaMundo.py

## Comandos
- git config --global user.name "Nombre de usuario" : Establece el nombre de usuario para los commits.
- git config --global user.email "miEmail@mail.com" : Establece el email para los commits (se recomienda que sea el mismo con el que estas dado de alta en GITHUB).
- git init : Inicializa un nuevo repositorio de Git en el directorio actual. 
- git remote add ALIAS URL-GTI-REPOSITORIO : Conecta el repositorio local a un repositorio remoto en GITHUB.
- touch "nombre del archivo" : Crea un nuevo archivo vacio.
- git add -A : Añade todos los cambios al area de preparación.
- git commit -m "mensaje de explicación" : Realiza la confirmación de los cambios en el area de preparacion con un mensaje breve y descriptivo sobre los cambios.
- git push ALIAS NOMBRE-RAMA : Envia los commits del repositorio local al repositorio remoto. 
- git status : Muestra el estado acutual del repositorio. 

  ## .gitignore
  .gitignore permite evitar que ciertos archivos suban al repositorio. Para este caso en particular se utilizó para los archivos con la extesión *.log*. Se puede observar en el repositorio remoto que el
  archivo *debug.log* no se encunetra, mientrasque en el repositorio local sí es visible. Esto refleja que *.gitignore* ha funcionado correctamnete.
  ## HolaMundo.py
  El progrma *HolaMundo.py* debe imprimir el mensaje "Hola Git". Aunque este mensaje no fue el inicial, la última versión del progrma corresponde a este mensaje. 
