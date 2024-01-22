# Demo 

some text here

## New branch

i am testing my new branch for a feature

## Understanding the workflow 
I ma trying to understand the git workflow. Pushing changes to the remote repo

## Pull Requets

manual pull requests worked. Now trying from github.com

## Workflow Summary

after making changes to your code;

- run git init ( the first step before below commands, this is to initiate a git repo on your local folder.)
- run git add . (use the full stop to add all the files or you can put file name instead)
- run git status (to check the status of the files)
- run commit -m "message" ( put the -m flag and replace 'message' with a real commit message. you can add two messages with two flags)

* remmember at this stage everything is local you need to send the changes to the repo on github.com

- run push -u branch_name ( if you set the upstream in the master you can just run git push otherwise you need to specify the name of the branch)

- run git log (to check recent commits' history)
- run git restore (to discard cganges to a file)?
- run git branch (to check number of branches avaiable and the ative one)
- run git -d branch_name (to delete a branch, use -D, with upper d to force delete)
- run git remote -v (to check available remote repo connections)