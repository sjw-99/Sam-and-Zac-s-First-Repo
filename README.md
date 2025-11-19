# Sam-and-Zac-s-First-Repo
## Everything we've learned about Git &amp; GitHub

Git is a version control tool

Git has 3 main states that your file can be contained within: 

-``` working directory```

The file has been altered but not yet committed to your database yet.

-```staging area```

Once added with the git command, this modified file is  being tracked by Git and is ready to be committed.

-```committed```

Altered file is now stored in the local database. 

![title](image/images.png)

## Restore, Revert and Reset

#### For undoing changes in development, there are 3 different commands

```restore```

This command 'restores' a file to its previously defined state - not updating your development history.

```revert```

Creates a new commit that reverts the changes made by other commits

```Reset```

Breaks source code beyond a desired commit. Updates your branch and changes commit history.

## Git Branches
Git organises different versions into branches. Different people collaborating on a repository may have different branches containing their work, separate from the 'main' or 'master' branch.

## Common Git Commands
- ### git status
    Shows the user which branch they're on, any unstaged changes, and any untracked files.
- ### git add 'file'
    Stages a file ready to be committed to your branch. Git now tracks this file.
- ### git commit -m "..."
    Commits the updated or new file to your git branch. '-m' is a tag that then adds the message "..." to your commit, describing the change(s) made.
- ### git checkout
    Allows the user to navigate between branches, or create a new branch using the '-b' tag.
- ### git merge 'target branch'
    Merges a user's branch back into the main branch, applying their changes to the main code body. Navigate to the target branch, then use the merge command followed by the branch you want to merge into it.

## The .gitignore File
By creating a .gitignore file within the working repository, the user/team can create a list of file types, directories, extensions etc. that git will automatically ignore. Pre-made template .gitignore files exist for most working environments that can be selected and edited when first creating a repository.

## Pulling from GitHub
To ensure that developers are starting in the same place, they should pull the current version of the code onto their branch. This is done using the command:

```git pull origin branch-name```

This will put the current version of all the repository files onto the user's branch, ready to be edited.

## Pushing to GitHub
Once a developer has built new code or fixed existing code, they can push their changes to their branch on GitHub using the following command

```git push remote-name branch-name```

The remote name is usually 'origin' but can be checked using ```git remote -v```. The changes will now be reflected in the user's branch of the repository on GitHub.

## Merging on GitHub
When changes have been made, a new feature has been built, or a bug has been fixed, a group of developers will then want to merge their work onto the main branch. This is done in browser on GitHub by creating a pull request. The pull request will scan for any merge conflicts, which then need to be reviewed and resolved by the team. Once this has been resolved, the branches can be merged and the main branch then reflects all the changes made.
