# 4 Git Storage
1. Working directory
2. Index
3. Repository
4. Stash

# Working Directory --> Index --> Repository

# Moving data to the Right
## 1. Moving data from Working Directory to Index
> git add filename  
> git diff
view different between working dir and index  
> git status  

## 2. Moving data from index to repostory
> git commit -m "Commit message"  
> git diff --cached 
view different between index and repository  
> git status  

## 3. Moving data from local repository to remote repository
> git push  

# View branch
> git branch

# view different between branch lisa and master
> git diff lisa master

# Switch to branch 'lisa'
> git checkout lisa

# Remove data from index
> git rm --cached filename
>
> rm filename

# Rename Files from menu.txt to menu.md
> rm menu.txt menu.md
>
> git add menu.md
>
> git add menu.txt

# Rename file from menu.md to menu.txt using git mv
> git mv menu.md menu.txt
