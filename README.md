echo "# masteruah" >> README.md

git init

md README.md


git add README.md

git clone git@github.com:Elena15022002/masteruah.git

git add .

git commit -m "commit inicial"

git push origin master

md privado.txt

mkdir privada

echo "privado.txt" > .gitignore

echo "/privada" > .gitignore

git add .

git commit -m "añadido fichero .gitignore"

md 1.txt

git add .

git commit -m "añadido 1.txt"

git tag v0.1

git push --tag origin master

git branch v0.2

git checkout v0.2

md 2.txt

git add .

git commit -m "añadido 2.txt"

git push origin v0.2

git checkout master

git merge v0.2 -m "merge v0.2 sin conflictos"

git checkout master

echo "Hola" >> 1.txt

git add .

git commit -m "hola en 1.txt"

git checkout v0.2

echo "Adios" >> 1.txt

git add .

git commit -m "adios en 1.txt"

git checkout master

git merge v0.2

vim 1.txt

git add .

git commit -m "arreglado merge en 1.txt"

git branch --merged

git branch --no-merged

vim 1.txt

git add .

git commit -m "arreglado merge en 1.txt"

git tag v0.2

git branch -d v0.2

git config --global alias.list 'log --oneline --decorate --graph --all'

git list



