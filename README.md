# 🕕 MI proyecto git 

- 📝 con el fin de aprender a utilizar los comandos 



git init     # Inicializa un repositorio en git
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
git config --global init.defaultbranch main
git branch --m main #cambiamos la rama a Main

git add .     # Agrega todos los archivos al area preparacion
git commit -m "Mensaje"  # Crea un nuevo commit con los cambios añadidos 


# VER HISTORIAL
git status #ver archivos modificado/no añadidos
git log  #ver historial de commits

# Eliminar archibos de seguimiento
git rm --cached archivo.txt

Revertir cambios
git revert #Crea un commit que revierte los cambios de un commit anterior


# trabajar con Ramas
git branch #ver ramas
git checkout -b nueva
git checkout main #volver a la rama principal


# subir a GitHub
Git remote add origin https: ////77
git push -u origin main

git clone https://github.

---

##  Sincronizar con GitHub

git fetch  # Descarga cambios del repositorio remoto sin aplicarlos

git merge origin/main  # Mezcla los cambios descargados con tu rama local

git pull origin main  # Hace fetch + merge (trae y aplica los cambios del repositorio remoto)
