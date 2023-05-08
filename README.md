If you need to update global gitignore run
cat *.gitignore >> ~/.gitignore_global
cat ~/.gitignore_global

To ignore previously tracked files run:
git rm -r --cached .
git add .
git commit -m "Drop files from .gitignore"
git push
