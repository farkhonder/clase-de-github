# clase-de-github
Comandos de github

Una vez instalas git, debes configurarlo:

git config --global user.name "name"
git config --global user.email. "xxxx@xxxx.com"

Generando tu public key:

ssh-keygen

leyendo tu llave para copiar a Github:

Cat ~/.shh/id.rsa.pub


arracando tu proyecto:
git init

//creas un archivo txt o readme 
touch README

//agregar el archivo
git add readme


//comentar primer comentrio
git commit -m "tu primer commit"

//subir el archivo
git push origin master