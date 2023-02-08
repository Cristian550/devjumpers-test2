gti clone https://github.com/Cristian550/devjumpers.git
cd devjumpers
touch README.md
git add .
git commit -m "commit inicial"
git push
touch privado.txt
mkdir privada
touch .gitignore
Se escribió dentro de .gitignore "/privado.txt" y "/privada" para que git los ignore.
touch 1.txt
git add .
git commit -m "privado.txt, privada, .gitignore y 1.txt creados"
git push
git branch v0.2
git checkout v0.2
touch 2.txt
git add .
git commit -m "rama v0.2 y 2.txt creada"
git push
git checkout main
git merge v0.2