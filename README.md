# Examples With Branches
Most important, make sure you have NOTHING in your working directory
either COMMIT or STASH your existing changes
## Types of Branches
* **The most important version** origin main (sometimes called master)
* **our local copy** local main (sometimes called master)
* **where we do our work** local feature branches 
*  **where we submit our work to be added to main** pushed feature branches
* **an intermediate branch we might use to put a lot of work together** aggregate branches 
## Common Commands
See a list of branches, (the current one will be marked with an asterix)
```
git branch
```
Create a new branch while staying on the current one
```
git branch <new-branch-name>
git branch feature-1
```
Move to an existing branch
```
git checkout <branch-name>
git checkout feature-1
```
Create and move to a new branch
```
git checkout -b <new-branch-name>
git checkout -b feature-2
```
Merge a different branch into this one.
```
git merge <other-branch>
git merge main
```