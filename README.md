## Installing Git ##
-Linux,Mac,Windows

-It doesn't matter what version is

-[Mac](https://git-scm.com/download/max)

-[Windows](https://git-scm.com/download/win)

## First time setup ##
1. System level:Affects all uses and repositories on the system
   
   file:/ete/gitconfig
3. Golbal level:Affects all repositories of a current user

   file:~/.config/git/config
5. Local level:Specific to the current repository
   
   file:.git/gitconfig

*git config --list -> You can see the config set.*

---

## Adding a new file to be staged ##
$ git add "file name"

$ git status


## Unstaging a file
$ git rm--cached "file name"

$ git status

## Ignoring a file ##
$ nano .gitignore

## Commit ##
$ git commit-m "commit message"

$ git log (Check what you've done)



