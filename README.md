# working-with-github

## Raising Pull Request (PR)

If you are working on internal team, create a branch on which you will be working
```
git checkout -b <branch-name>
```
For example
```
git checkout -b quiz
```
Make the changes which needs to be done for spefic requriement
```
// Note: To stage the changes file so that it can be commited, we need to add it first
git add . // add all the changed files 
git commit -m "you comment message"
git push origin -u quiz // Upstream
// if you are pushing your branch for first time
```
Come to GitHub and raise the PR

## Working on Review Comments

Replay to all the comments you have received, and again commit the updated changes (follow the same command above to commit and push the new changes).

## Merging the Code

Once the code has been merged successfully, it can be deleted.

## Smart Commits with Jira & GitHub
```
git add . // stage changed files
git commit -m "<jira task id(ISSUE_KEY)> #commit <commit message>"
```
Example
```
git commit -m "JHD-33 #commit tested smart commit
```
