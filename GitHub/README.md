# Git / GitHub

Git es un software que vas a instalar en tu computadora. Es una herramienta básica en el desarrollo de software y análisis de datos. 
         
- Instalar Git ( https://git-scm.com )

- Crear cuenta en GitHub (github.com)
   - Dar click en 'New' para crear un repositorio
   - Indicar nombre del proyecto
   - Indicar _Privado_ o _Publico_
   - Crear
   - Seguir instrucciones en la terminal

   - Crear **Token**

- Crear directorio donde estará el contenido del repositorio
- Crear README.md y notebooks
> En una terminal:

     $ echo "# Mi proyecto" >> README.md _(en caso que no se haya creado anteriormente)_
     $ git init
     $ git add .
     $ git status
     $ git commit -m "first commit"
     $ git status
     $ git branch -M main
     $ git remote add origin https://github.com/alrakomala/myRepo.git
     $ git push -u origin main

- abrirá ventana para introducir nombre de usuario y token

Listo :exclamation: 

Se pueden hacer cambios en los documentos locales o directamente en github.com

> Despues de hacer cambios de manera local:

     $ git status
     $ git add .
     $ git commit -m "indicar modificacion"
     $ git push 

> Despues de hacer cambios en github.com (o cuando es un proyecto compartido, etc...):
     $ git pull

para registrar los cambios en nuestra carpeta local. 




