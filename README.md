# webpage


git clone https://github.com/nikolajwinther/webpage.git
cd webpage/
git branch homepage
git checkout homepage 
nano index.html
git add index.html 
git config --global user.name "nikolajwinther"
git config --global user.email "nikolajwinther@gmail.com"
git commit
[Inside git commit: write commit log text]
git status
git log
git log --decorate --oneline --graph --all
git push origin homepage
git status
git checkout master
git pull
git checkout homepage
