# dom learning to use git :)

## Commands used 

- git init: Create a repository
- git status: Compare working directory, stage and commited branch
- git add: Add changes from working directory to the stage
- git commit: Commit changes from the stage to current branch 
- git config: Set or get cnfigortaion
- git log: Show history of project commits
- git branch -c: Create a new branch 
- git checkout: Checkout (switch to) a specified branch
- git branch: displays a list  of branches, with current branch highlighted
- git checkout -b: To create and switch to a new branch (updates HEAD)

## What's a branch?

A branch is a ref(erence) to a commit. When HEAD points to a branch we say we are 'on' that branch. When we make
a commit while we are on a branch, the branch is updated to ref(er) to the new commit.

## What's HEAD?

HEAD is a ref(erence) points to the 'current' commit or branch that I am on. Git commands like: 'log', 'status and
 'branch' use head. 'git checkout' updates HEAD to point to a different branch.
 
Default editor is notepad++ (can be changed)
Or use 'git commit -m "<message>"'

- First line should be clear, accurate and concise
- Use proper spelling, punctuation and grammar
- Don't end in fullstop ' . '