#Intro to Git

### Requirements
Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and a text editor of your choice

### Steps

1. Fork the repository by pressing the "fork" button. This creates a copy of the repository under your account.
2. Enter the new repository you forked. Click "clone or download" and copy the "Clone with HTTPS" link
3. Open git bash and use cd to where you want to store your Git repositories
4. Type into the terminal
`git clone {insert-url-here}` (remove the curly brackets)
5. use `cd {name-of-folder}` to move into the directory you just created and `ls` to see what folders/files are in your current working directory
6. Create a new branch `git checkout -b "name-of-branch"`
7. Make edits to the index.html file
8. Add and commit the change using `git add .` and `git commit -m "description of commit"`
9. Switch to master `git checkout master`
10. Merge your new branch to master `git merge name-of-branch`
11. Make a change on the master branch, then add and commit
12. Switch to your other branch and make a different change on the same line
13. Add and commit these changes on your other branch `git add .` `git commit -m "description of commit"`
14. Switch back to master and merge `git checkout master` `git merge name-of-branch`. This will create a merge conflict.
15. Fix merge conflicts
16. Add, commit, and push `git push origin master`(push updates the remote repository on Github)
