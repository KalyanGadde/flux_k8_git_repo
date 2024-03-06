Quick setup — if you’ve done this kind of thing before
or	
	
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.



create a new repository on the command line
```
echo "# flux_k8_git_repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/KalyanGadde/flux_k8_git_repo.git
git push -u origin main
```

…or push an existing repository from the command line
```
git remote add origin https://github.com/KalyanGadde/flux_k8_git_repo.git
git branch -M main
git push -u origin main
```
