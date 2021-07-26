# git

git config --global user.name "yourgithubname"
git config --global user.email "yourgithubemail"

git init
git add .
git commit -m "fill with your want"
git commit -am "fill"
git status

alias graph="git log --all --decorate --oneline --graph"
graph

git remote
git remote -v
git push
