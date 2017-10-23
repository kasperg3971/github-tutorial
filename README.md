# GitHub Tutorial

**_by Kasper Gacek :)_**

---
## Git vs. GitHub
* Git is a command
    * example:` git init`
* Github is a repository where you have all your files and directory



---
## Initial Setup



<p align = "center">
  <img src = "Capture.PNG" width="500" height="377">
</p>

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
 
 kasperg3971:~/workspace/github-tutorial (master) $ git push
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
Counting objects: 6, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.20 KiB | 1.20 MiB/s, done.
Total 6 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To github.com:kasperg3971/github-tutorial.git
   e39e756..41b1018  master -> master
 

```
1. git init: initializes the code to get ready for the commit 
2. git status: checks if the files are green(changed, added files) or red (old,not changed, new)
3. git add . : adds the file to get ready for committing
4. git commit -m "": saves/screenshots the file with a saved message.
5. git push: adds the commit to the repository






---

## Workflow & Commands

* `mkdir` : creates a directory
*  `cd` : goes into the child directory or file within the current directory
*  `cd .. ` : goes back to previous directory or parent directory
*  ` ~` : returns to the root
*  `pwd` : lists the current specific directory all the way to its parents directory and root
*  `ls` : lists all the child directorys or files within the directory
*  `rmdir` : removes a empty directory
*  `touch` : creates a file
*  `rm` : removes a file
*  `rm -f`: removes directory by force
*  `mv`: can be used for two things, it can be used for moving things,ex:` mv file1.txt existingfile.txt`, or it could be used for renaming a file, ex: `mv file1.txt newnamefile.txt`
*  `/`: helps travel quicker to a child's child directory
*  `clear` : saves data but clears canvas
*  `(control C)` & ` (control D)`: Control c creates a new line for you to type on while control d puts the local host in front of the local host
*  `↑` : Goes to your previous commands
*  




---
## Rolling Back Changes
This section will explain the foundations of undoing git commands
* 
