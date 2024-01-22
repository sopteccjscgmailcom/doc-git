1. [config]
git config --global user.name "sopteccjscgmailcom"
git config --global user.email "sopteccjsc@gmail.com"

2. [init]
git init

3.  [branch]
git branch -m main          

4.  [status]
git status                      

5.  [add]
git add *
git add leeme.txt       

6.  [commit]
git commit -m "primer commit"   

7.  [log](log.md)                     
git log                         {muestra commits

8. [checkout]
git checkout <nombredelarchivo> {restaura los cambios antes de subir al stage

9. [reset]
git reset                       {deshace cambios agregados al area de stage (git add)

10. [diff]
git diff                        {ver las difrencias entre nuestros archivos recien editados

11. [reflog]
git reflog                      {muestra el historial completo de interacciones en git un log completo

12. [tag]                       
git tag version_1               {agregamos un nombre a nuestra version de nuestro proyecto

13. [branch]                    
git branch rama1                {creamos una rama

14. [switch]
git switch nombreDeLaRama       {cambiamos de lugar de trabajo a otra rama

15. [merge]
git merge otrarama              {combina 2 ramas

16. [stash]
git stash                       {un commit temporal

<!----------------------------- GITHUB ----------------------------->

17. [remote]                    {nos conectamos al repositorio de github
git remote add origin https://github.com/sopteccjscgmailcom/doc-git.git

18. [push]                      {
git push -u origin main