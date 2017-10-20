# GitHub Tutorial

**_by Kasper Gacek :)_**

---
## Git vs. GitHub
* Git is a command
    * example:` git init`
* Github is a repository where you have all your files and directory



---
## Initial Setup




---
## Repository Setup
```html


kasperg3971:~/workspace/github-tutorial (master) $ git init
Reinitialized existing Git repository in /home/ubuntu/workspace/github-tutorial/.git/
kasperg3971:~/workspace/github-tutorial (master) $ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
kasperg3971:~/workspace/github-tutorial (master) $ git add .
kasperg3971:~/workspace/github-tutorial (master) $ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   README.md
        
kasperg3971:~/workspace/github-tutorial (master) $ git commit -m "Tutorial complete"
[master f0b4ab2] Tutorial complete
 1 file changed, 5 insertions(+), 1 deletion(-)
 

```
1. git init: initializes the code to get ready for the commit 
2. git status: checks if the files are green(changed, added files) or red (old,not changed, new)
3. git add . : adds the file to get ready for committing
4. git commit -m "": saves/screenshots the file with a saved message.





---

## Workflow & Commands



---
## Rolling Back Changes