## 🛠️ Comenzar desde cero


## Inicializa un nuevo repositorio Git.
#Git init


#git config --global user.name "Tu Nombre"
#git config --global user.email "tu@email.com"
Configura tu nombre y correo (solo la primera vez).

git config --global init.defaultBranch main  #Cambia la rama principal por defecto a main.

## Renombra la rama actual a main.

#git branch -m main



## 📥 Agregar y confirmar cambios

git add .

## Agrega todos los archivos al área de preparación.

#git commit -m "Mensaje"

#Crea un nuevo commit con los cambios agregados.


## Ver historial
#git status

#Muestra el estado de los archivos (nuevos, modificados, no seguidos).

## Muestra el historial de commits.
#git log


## Archivos individuales

#git add archivo.txt

## Agrega un archivo específico.

#git rm --cached archivo.txt

#Elimina un archivo del control de versiones (pero no lo borra del proyecto).

## Revertir cambios

#git reset --hard <hash>
#Revierte todo al commit indicado (elimina cambios posteriores).

## Trabajar con ramas

#git branch
#git checkout -b nueva
#crea y cambia a una nueva rama.

## Cambia de nuevo a la rama principal.
#git checkout main

# Subir a GitHub

#git remote add origin https://github.com/usuario/repositorio.git

# Conecta tu proyecto local con GitHub.

#git push -u origin main
#Sube tu proyecto a GitHub por primera vez.

## Sincronizar con GitHub

#git fetch

## Descarga cambios del repositorio remoto sin aplicarlos.

#git merge origin/main
#Aplica los cambios descargados a tu rama actual.

##git pull origin main
#Descarga y aplica los cambios del repositorio remoto (fetch + merge).
