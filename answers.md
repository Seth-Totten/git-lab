Answer 1- git version 2.32.0 
user.name = Seth Totte user.email = st200820@ohio.edu
A window explaining the add command comes up
Changes to be committed, new file: README.md; Changes not staged for commit: modified: README.md; Untracked files: answers.md
README.md is no longer "not staged for commit"
Both README.md and answers.md have Changes to be committed, and neither are untracked files now. 
It now says at the bottom that there are no changes added to commit, and that answers.md has Changes not staged for commit, most likely becuase I keep typing in it and updating it.
Answer 8:: commit 0a9890ea22fd7fa9cb1008f3b639e83b5c6c2bce (HEAD -> master)
Author: Seth Totten <st200820@ohio.edu>
Date:   Tue Jan 18 11:06:34 2022 -0500

    Initial commit
Answer 9:On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
    modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
sethtotten@Seths-MacBook-Pro git-lab % 
Answer 10 ::The changes I made online were not updated in the local copy. 
Answer 11 ::  ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Seth-Totten/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
sethtotten@Seths-MacBook-Pro git-lab % 
Answer 12 :: Now the changes made online are appearing in the local copy.
Answer 13 :: sethtotten@Seths-MacBook-Pro git-lab-2 % ls -a
.        ..        .git        .gitignore    README.md

Commit message: Good luck

