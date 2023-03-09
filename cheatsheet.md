# My Git Cheatsheet

## Initialize Git
``` git init ```

## Clone a git repo
``` git clone https://github.com/git/git.git ```

## Check Git status
``` git status ```

## Powershell command to create file

``` New-Item "git-cheat-sheet.md" -ItemType File ```

## Bash command to create file

``` touch "git-cheat-sheet.md" ```

## Add code to git

``` git add cheatsheed.md ```

## Take source code snapshot for tracking

``` git commit -m  'my cheatsheet' ```

## Check the history of commits in current branch

``` git log ```

## Branch - Isolate code using branch
* List branch

``` git branch ```

* Create branch

``` git checkout -b features/1234-new-killing-feature ```

* Delete branch

``` git checkout -d features/1234-new-killing-feature ```

* Add the isolated source code to branch

``` git merge features/1234-new-killing-feature ```
* head refers to the current branch or commit that you have checked out
* HEAD refers to the pointer to the current branch or commit

## Git Fetch
retrieve code from repo

``` git fetch ```