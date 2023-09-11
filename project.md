project

## Conceptual

git respitory is single collection and track modification of the document offline

 git hub difference resporities which you want version control online

Develop area is the folder where project is developed is is in your local computer

local resporitory  where you save you snapshots. it is found in` .git` folder in your PC

staging area is the location used to prepare new snapshots to the timeline, it is an intermediate level to transfer from the develop area to your local repritsory locally in your CP

To check in what conceptual area my file is i can use `git status`

## Manual of git commands

1 how to initilize git

`.git init`

2 how to send to the staging areas

`git add <file name>`

3 How to command a change to creat my 1st snapshots

`git commit -m "meaning full message"`

P.S menaing full msg: why,What, How, limitation, effect

4 How to check in what conceptual area my files are

`git status`

git status will tell me uncommited, unstaged, untracked files

 Testing what happen if I don't use -m

5 how to get history `git log` provides the list of your commands

`git log -n `

`git log --abbrev-commit`

`git log --help`

6 how to compare versions of the same line  travelling in time you can use  either `git show <commit ID> <CommitID>` or `git diff <commit ID> <Commit ID>`

`git show -2 <file name> `to track the last version




How to bring changes from remote to the local 
git pull
You need to use git pull if you are collaborating or remotely you modified the document


