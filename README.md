mkdir Exercicio01
cd Exercicio01
git init
git config --global user.name "Fabricio Reis"
git config --global user.email "fabricio.reis@aluno.impacta.com.br"
ls .git

ls
echo 01 > arquivo.txt
ls arquivo.txt

git add .
git status

git commit -m "git add example - arquivo.txt"
git status

echo 02 > arquivo.txt
git diff
git add .
git status

git diff
echo 03 > arquivo.txt
git add .
git diff 
git status

git restore arquivo.txt
git status

git commit -m "Primeiro Commit - Arquivo.txt"
git log


vi .gitignore
cat .gitignore

echo > novo.txt
ls
git status
