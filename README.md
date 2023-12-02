# MaitriseGit

ssh-keygen -t rsa -b 4096 -C najifiddo@gmail.com

cat ~/.ssh/id_rsa.pub

git config --global user.name "Abderraouf Naji"
git config --global user.email "najifiddo@gmail.com"

ssh -T git@github.com
git clone git@github.com:AbderraoufNaji/MaitriseGit.git
cd MaitriseGit
touch index.html
git commit -m "Premier commit:ajout d'index.html
echo "contenu d'index "> index.html
git add index.html
git commit -m "Premier commit:ajout d'index.html"

 git log

 git branch ma-fonctionnalite
 git checkout ma-fonctionnalite

 git add .
 git commit -m "Modification de ma-fonctionnalite"
 git push origin ma-fonctionnalite
 git checkout ma-fonctionnalite
 git commit -am "Modification dans ma-fonctionnalite"
 git checkout master
 git commit -am "Modification dans master"
 git merge ma-fonctionnalite
 git add .

 git commit -m "Résolution du conflit"
 git flow feature start ma-fonctionnalite
 git flow release start ma-version
 git flow feature finish ma-fonctionnalite
 git flow hotfix start mon-correctif
