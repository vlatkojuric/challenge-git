## Useful commands in order I think

- git init -creates a special folder to hold all of your snapshots

- ls -la - good to use to list all of the files in a folder,the hidden ones too
  (out of order )

- git add . -adds everything to the staging area

- git commit - adds everything in staging area to the repository as a snapshot

- git-status - shows everything in the staging area

## Branches

- when we want to try something without messing up our code,we can make a branch from our _main code_ and we can make all of our changes in that branch,and if we like it,we can _merge_ it from that branch into our main code,if not,delete it

- git branch (name) - creates a new branch for you to make changes without affecting the rest of your code

- git checkout(name) - moves you to your new branch where you can make changes without affecting the rest of your code

- git merge (branch) - adds changes from other branch to main

- git remote add origin - add the SSH key from your repository to connect the repository on Github with the one on your local device

- git push -u origin main - final step to push code from your local device repository to your remote repository on Github
