CS 2211 - Code Bank
===================

Repo contains code for study questions.

The easiest way to submit new code is by creating pull requests.

How To Contribute
_________________

* [Install Git](http://git-scm.com/book/en/Getting-Started-Installing-Git) on your device.
* [Create a github account](https://github.com/join)
* [Fork the Repo](https://github.com/h3llborn/2211/fork) to your profile.
* Clone your fork to your computer
`git clone https://github.com/YOURUSERNAME/2211.git`
* Add upstream to remote github directory
```
git remote add upstream https://github.com/h3llborn/2211.git
git fetch --all
git pull --rebase upstream master
git push
```
* Create a branch to work on, name it after the program
```
git checkout -b PROGRAMNAME master
git clean -df
git pull --rebase upstream
```
* Push just created branch to your repo as backup
`git push origin PROGRAMNAME`
* Now that you have created your branch to work on, make changes to the code
* Next Stage them
```
git status
git add -A
```
* Commit changes
```
git commit -m "Programname: what you did"
git push
git pull --rebase upstream master
git checkout master
git pull --rebase upstream master
```
* On your github submit a 'pull request' of your branch to the main repo. [About pull-requests](http://help.github.com/send-pull-requests/)	
