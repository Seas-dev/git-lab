** Answer 1 **
git version 2.17.1


** Answer 2 **
user.name=Seas-dev
user.email=seastedt.ej@gmail.com


** Answer 3 **
The git --help command gives you all the argmuents and options you can use after the "git" command. It also give some common use cases of the git command.

usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]


** Answer 4 **
jseasted@odd35:~/Documents/cs2400/Labs/git-lab$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)


** Answer 5 **
jseasted@odd35:~/Documents/cs2400/Labs/git-lab$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md


** Answer 6 ** 
jseasted@odd35:~/Documents/cs2400/Labs/git-lab$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md


** Answer 7 ** 
jseasted@odd35:~/Documents/cs2400/Labs/git-lab$ git status
On branch master
nothing to commit, working tree clean


** Answer 8 **
jseasted@odd35:~/Documents/cs2400/Labs/git-lab$ git log
commit b995b3c692ec2a1adf65df813b1a2d494d7f0782 (HEAD -> master)
Author: Seas-dev <seastedt.ej@gmail.com>
Date:   Fri Sep 3 16:53:32 2021 -0400

    Initial Commit

** Answer 9 **
jseasted@odd35:~/Documents/cs2400/Labs/git-lab$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean


** Answer 10 ** 
The changes I made online were not reflected in my local copy.


** Answer 11 **
This is the output I received when trying to push without pulling the changes:
To https://github.com/Seas-dev/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Seas-dev/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


** Answer 12 **
Once I ran the git pull command, my local copy of README.md was updated with the changes made online



