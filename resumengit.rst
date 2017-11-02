#####################
Resumen de uso de git
#####################

Para iniciar un repositorio
===========================

- crear projecte en github/bitbucket/...

  Recomiendo: crear readme

- copiar enlace del github

- desde la carpeta que nos interese guardar el proyecto ::

    $ git clone enlacedelgithub
    $ cd nombrecarpeta

- es posible que tengas que configurar tu máquina para hacer commits ::

    $ git config --global user.email "midirección@example.com"
    $ git config --global user.name "minombre"


Para empezar día de trabajo
===========================

- traer cambios del repositorio remoto ::

     $ git pull origin master

- trabajar: hacer cambios en los ficheros

- ver cambios ::

     $ git status
     $ git diff nomfitxer

- añadir cambios ::

     $ git add .

- registrar cambios ::

     $ git commit -am "mensaje sobre los cambios realizados"

- enviar al repositorio remoto ::

     $ git push origin master


