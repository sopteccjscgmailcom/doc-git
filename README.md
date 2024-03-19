```css
h1{
background:red;
}
```

# documentacion git

## 🟡1 CONFIGURACION

### [config](2_Configuracion_git/config.md)
```bash
git config user.name "sopteccjscgmailcom"
```
    git config user.email "sopteccjsc@gmail.com"

### [init](2_Configuracion_git/init.md)
    git init

### [branch](3_Funcionalidades/branch.md)
    git branch -m main          

### [status](2_Configuracion_git/status.md)
    git status                      

### [add](2_Configuracion_git/add.md)
    git add *
    git add leeme.txt       

### [commit](2_Configuracion_git/commit.md)
    git commit -m "primer commit"   

## 🟡2 Funcionalidades

### [log](log.md)                     
    git log                         
muestra commits

### [checkout](3_Funcionalidades/checkout.md)
    git checkout <nombredelarchivo>
restaura los cambios antes de subir al stage

### [reset](3_Funcionalidades/reset.md)
    git reset                       
deshace cambios agregados al area de stage (git add)

### [diff]
    git diff                        
ver las difrencias entre nuestros archivos recien editados

### [reflog]
    git reflog                      
muestra el historial completo de interacciones en git un log completo

### [tag]                       
    git tag version_1               
agregamos un nombre a nuestra version de nuestro proyecto

### [switch]
    git switch nombreDeLaRama       
cambiamos de lugar de trabajo a otra rama

### [merge]
    git merge otrarama              
combina 2 ramas

### [stash](3_Funcionalidades/stash.md)
    git stash                       
un commit temporal

## 🟡3 GITHUB
subida de proyecto
### [remote]                    
    git remote add origin https://github.com/sopteccjscgmailcom/doc-git.git
nos conectamos al repositorio de github - solo la primera vez

### [push]                    
    git push -u origin main
subir nuestro proyecto - luego usamos solo push

### [fetch]
    git fetch                       
descarga el historial de cambios

### [pull]
    git pull                        
combinamos remoto con local

## 🟡4 Descargar un proyecto
### [clone]
    git clone https://github.com/sopteccjscgmailcom/doc-git.git     
copia sincronizada del proyecto

## 🟣 trabajar con otro proyecto en la pagina de github NO-local

fork   <creamos un fork>        
clone   <una vez creado clonamos nuestro repositorio y empezamos a trabajar>
Contribute  ->  pull request    <una vez haciendo add, commit, en github hacemos el pull>

sinc fork   <para que estemos actualizador con el proyecto original>

## 🟣 Tipos Adicionales
### abrir nuestra visual estudio code en la ruta donde nos encontramos 
    code .

### ingresamos a esta ruta para ver la configuracion de nuestro git
    C:\Users\clive_pfl66ry\.gitconfig
donde veremos nuestro user y email

### lo usamos para evitar ficheros que no queremos agregar
[.gitignore](.gitignore)

### comentamos el codigo en visualStudio
    crlt + }
