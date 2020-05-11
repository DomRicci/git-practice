# dom learning to use git :)

## Commands used 

- git init: Create a new git repository
- git status: Compare working directory, stage and commited branch
- git add: Add changes from working directory to the stage
- git commit: Commit changes from the stage to current branch 
- git config: Set or get cnfigortaion
- git log: Show a history aka("log")of project commits. Has lots of arguements, can take '--author <string>' and '--since' or '--until'. 
	some other useful aaguements are '--oneline' and '--graph'
- git checkout: checkout branch (update HEAD and apply changes to working directory)
- git checkout -b: To create and switch to a new branch (updates HEAD)
- git branch: displays a list  of branches, with current branch highlighted
- git branch -c: Create a new branch 
- git merge: merge changes from different branches
- git merge --abort: Abort a merge in progress
- git log branch1..branch2: log of all commits in branch2 that don't exist in branch1
- git log branch1...branch2: Log of all commits in either but not both
- git show: Show a single commit
- git merge --no-commit -no-ff: Attempt to merge but don't automerge or ff merge
- git branch --no-merged branch1: list branches with unmerged conflicts
- git branch --merged branch1: List branches rhat have no unmerged conflicts
- git diff: Can take multiple arguements, can show various details comparing two commits. Use 'git help diff' to get more information


## What's a branch?

A branch is a ref(erence) to a commit. When HEAD points to a branch we say we are 'on' that branch. When we make
a commit while we are on a branch, the branch is updated to ref(er) to the new commit.

## What's HEAD?

HEAD is a ref(erence) points to the 'current' commit or branch that I am on. Git commands like: 'log', 'status and
 'branch' use head. 'git checkout' updates HEAD to point to a different branch.
 
## Commit messages 
 
Default editor is notepad++ (can be changed)
Or use 'git commit -m "<message>"'
- First line should be clear, accurate and concise
- Use proper spelling, punctuation and grammar
- Don't end in fullstop ' . '

## Merging

Merging means to bring the changes from one branch to another.
- A fast forward merge happpens when the target branch was branched from the current one, and no more recent commits have happened to the current branch.
- An Automatic merge happens when the two histories have divered, but git is able to reconcile them into a single commit, on the current branch.

## Resolving a merge conflict 

1. Don't panic!
2. Edit files to resolve conflict
3. Add and commit changes (use commands above)



