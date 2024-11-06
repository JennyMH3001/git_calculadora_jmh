Hola soy Jenny 
Nombre de repositorio: git_calculadora_jmh

#Crear una rama para una nueva función
git checkout -b suma-feature

#Realizar cambios y agregar archivos
git add calculadora.py
git commit -m "comentario"

#Fusionar cambios en Development
git checkout Development
git merge suma-featura

#Subir cambios a Github
git push --set-upstream origin suma-feature
git push

#Cambios del GitHub
Git pull
