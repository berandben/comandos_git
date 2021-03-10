https://www.atlassian.com/es/git  




# comandos_git  

Descarga git  
https://git-scm.com/  

ssh-key  

genera key ssh  



Inicializa repositorio  
git init  

Crea usuario
General  
git config --global user.name"nombreusuario"  
git config --global user.email"tuemail@email.com"  

Para un repo concreto  
git config user.name"nombreusuario"  
git config user.email"tuemail@email.com"  

Elimina usuario  
git config --global --unset-all user.name  
git config --global --unset-all user.email  

Añade archivos  
git add miarchivo.txt  
git add .  (todos los archivos)  

Crea un commit  
git commit -m "mi primer commit"  
git commit -a -m 'otro commit'  

Enlaza repositorio externo  
git remote add origin https://urldelrepositorio

Sube al repositorio externo  
git push -u origin master

Descarga los archivos remotos  
git pull

Descargar/Clonar repositorio  
git clone urldelrepositorio  

Muestra configuración general  
git config --global --list  

Muestra el estado  
git status  

Muestra el registro de commits  
git log  
git log --oneline --decorate

Crea una nueva rama  
git checkout -b minuevarama (versión abreviada)  

git branch minuevarama (crea la rama)  
git chekout minuevarama (se mueve a esa rama)  

Visualiza las ramas  

git branch  



Cambia de rama  
git chekout ramaalaquequieromoverme  

Une ramas  
git checkout ramadedestino  
git merge ramaafusionar  

Elimina rama  
git branch -d ramaaeliminar  

Crea tags  
git tag nombretag -m "comentario"  

Sube tags  
git push --tags  

















