```
rm -rf .git
git init
git branch -M gh-pages
git remote add origin git@github.com:Coder-Heroes/burning-man.git
git add .
git commit -m 'first commit'
git push origin gh-pages --force
```