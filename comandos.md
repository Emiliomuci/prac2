sudo apt install git-all
git --version
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
git config --list
git config --global alias.st status
git config --global alias.logone "log --oneline"
git config --global init.defaultBranch <nombre_rama>

git add index.html
git add *
git commit -m "mensaje"
git commit -am "mensaje"

git status
git log
git log --oneline
git show <id_commit>
git diff
git diff --staged

git reset --soft <id_commit>
git reset --mixed <id_commit>
git reset --hard <id_commit>

git restore <archivo>
git restore --staged <archivo>
git restore --source=<id_commit> <archivo>

git checkout -- <archivo>
git checkout <id_commit>
git checkout <nombre_rama>
git checkout -b <nombre_rama>

git branch
git branch -m <nuevo_nombre_rama>
git branch -d <nombre_rama>
git push -d <nombre_remoto> <nombre_rama>

git remote add origin <URL_REPO>
git remote set-url origin <URL_REPO>

git push -u origin main
git push
git pull
git clone <URL_REPO>

git merge <nombre_rama>
git merge --abort

gitk
git remote add upstream <URL_REPO>
