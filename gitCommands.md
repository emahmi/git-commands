# Most commonly used git commands

### Table of content

- [Using Git Init Command](###using-git-init-command)
- [Using Git Clone Command](#using-git-clone-command)
- [This will disassociate the downloaded current repository from the origin.](#this-will-disassociate-the-downloaded-current-repository-from-the-origin)
- [Using Git Branch to create a new branch](#using-git-branch-to-create-a-new-branch)
- [Command to view all branches](#command-to-view-all-branches)
- [Git command to delete a branch](#git-command-to-delete-a-branch)
- [Using Git Checkout Command](#using-git-checkout-command)
- [Using Git Add Command](#using-git-add-command)
- [Using Git Commit Command](#using-git-commit-command)
- [Using Git Push Command](#using-git-push-command)
- [Using Git Pull Command](#using-git-pull-command)
- [Using Git Status Command](#using-git-status-command)
- [Using Git Log Command](#using-git-log-command)
- <i>If you want to learn git concepts you can visit a website by <a href='https://dev.to/unseenwizzard/learn-git-concepts-not-commands-4gjc'>Clicking here</a></i>

### Using Git Init Command

    $ git init

### Using Git Clone Command

    $ git clone <https://url-of-the-repository>

### This will disassociate the downloaded current repository from the origin.

    $ git remote rm origin

### Using Git Branch to create a new branch

    $ git branch <branch-name>

### Command to view all branches

    $ git branch

### Git command to delete a branch

    $ git branch -d <branch-name>

### Using Git Checkout Command

    $ git checkout <branch-name>

> or you can use switch instead of checkout

    $ git switch <branch-name>

### Using Git Add Command

    $ git add <file-name>

> or Add all files

    $ git add .

### Using Git Commit Command

    $ git commit -am “<commit-message>”

### Using Git Push Command

    $ git push <remote> <branch-name>

### Using Git Pull Command

    $ git pull <remote>

### Using Git Status Command

    $ git status

### Using Git Log Command

    $ git log
