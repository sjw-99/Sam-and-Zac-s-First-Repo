# Sam-and-Zac-s-First-Repo
Everything we've learned about Git &amp; GitHub

## What is Git?
Git is a version control tool.

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