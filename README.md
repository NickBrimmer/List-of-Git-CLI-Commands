# List-of-Git-CLI-Commands
Just a list of common Git CLI Commands


## Setup

set a name that is identifiable for credit when review version history

```git config --global user.name <firstname lastname>```


set an email address that will be associated with each history marker

```git config --global user.email [valid-email]```


set automatic command line coloring for Git for easy reviewing

```git config --global color.ui auto```




## Branch and Merge

```git branch```
list your branches. a * will appear next to the currently active branch


```git branch [branch-name]```
create a new branch at the current commit


```git checkout```
switch to another branch and check it out into your working directory


```git merge [branch]```
merge the specified branch’s history into the current one


```git log```
show all commits in the current branch’s history


## Ignoring Patterns


## Inspect and Compare

```git log```
show the commit history for the currently active branch


```git log branchB..branchA```
show the commits on branchA that are not on branchB


```git log --follow [file]```
show the commits that changed file, even across renames


```git diff branchB...branchA```
show the diff of what is in branchA that is not in branchB


```git show [SHA]```
show any object in Git in human-readable format


## Re-Write History


## Share and Update


## Stage & Snapshot


## Setup & Init

```git init```
initialize an existing directory as a Git repository


```git clone [url]```
retrieve an entire repository from a hosted location via URL


## Temporary Commits


## Tracking Path Changes



