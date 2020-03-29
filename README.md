# comandos_git  

Descarga git  
https://git-scm.com/

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

Enlaza repositorio externo  
git remote add origin https://urldelrepositorio

Sube al repositorio externo  
git push -u origin master  

Muestra configuración general  
git config --global --list  

Muestra el estado  
git status  

Muestra el registro de commits  
git log  




