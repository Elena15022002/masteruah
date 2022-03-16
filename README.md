git init
git add README.md
git config --global user.name "ElenaAyllon"
git config --global user.email eleayme2002@gmail.com
git commit -m "Commit inicial"
git clone git@github.com:Elena15022002/masteruah.git
git remote add origin https://github.com/Elena15022002/Elena15022002.git
git push origin master
echo "Fichero1" >> fichero1.txt
git tag  v0.1
git branch v0.2
git checkout v0.2
touch 2.txt
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
git tag v0.2
git branch -d v0.2
git config --global alias.list 'log --oneline --decorate --graph --all'
git list


