***path***
git --version
git version 2.38.1.windows.1

***path***
mkdir dummy-proj-for-git

***path***
cd dummy-proj-for-git/

C:/Users/Epitome/Desktop/BACKEND/GIT/dummy-proj-for-git/.git/

***path***/dummy-proj-for-git
ls

***path***/dummy-proj-for-git
ls -a
sktop/BACKEND/GIT/dummy-proj-for-git
git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

***path***/dummy-proj-for-git
touch index.js

***path***/dummy-proj-for-git
cat index.js
console.log("Hello from git");

***path***/dummy-proj-for-git
git status
On branch master

No commits yet

Untracked files:
(use "git add <file>..." to include in what will be committed) git-Command.md
index.js

nothing added to commit but untracked files present (use "git add" to track)

***path***/dummy-proj-for-git
git remote

***path***/dummy-proj-for-git
git add index.js

***path***/dummy-proj-for-git
git status
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)
new file: index.js

Untracked files:
(use "git add <file>..." to include in what will be committed) git-Command.md

***path***/dummy-proj-for-git
git status
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)
new file: index.js

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)  
 (use "git restore <file>..." to discard changes in working directory)
modified: index.js

Untracked files:
(use "git add <file>..." to include in what will be committed) git-Command.md

***path***/dummy-proj-for-git
git commit -m "Added first commit"
[master (root-commit) 4d99528] Added first commit
1 file changed, 1 insertion(+)
create mode 100644 index.js

***path***/dummy-proj-for-git
git log
commit 4d99528c62287ef212baddf53667a59f633847ae (HEAD -> master)Author: Adarsh <jha01adarsh@gmail.com>
Date: Thu Jul 13 01:19:58 2023 +0530

    Added first commit

***path***/dummy-proj-for-git
git status
On branch master
Changes not staged for commit:
(use "git add <file>..." to update what will be committed)  
 (use "git restore <file>..." to discard changes in working directory)
modified: index.js

Untracked files:
(use "git add <file>..." to include in what will be committed) git-Command.md

no changes added to commit (use "git add" and/or "git commit -a")

***path***/dummy-proj-for-git
git add .

***path***/dummy-proj-for-git
git status
On branch master
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: git-Command.md
modified: index.js

***path***/dummy-proj-for-git
git commit -m "Git commands added"
[master d1f965f] Git commands added
2 files changed, 81 insertions(+), 1 deletion(-)
create mode 100644 git-Command.md

***path***/dummy-proj-for-git
git log
commit d1f965f5c6d0e2c866e761ce6e16098233938119 (HEAD -> master)Author: Adarsh <jha01adarsh@gmail.com>
Date: Thu Jul 13 01:28:51 2023 +0530

    Git commands added

commit 4d99528c62287ef212baddf53667a59f633847ae
Author: Adarsh <jha01adarsh@gmail.com>
Date: Thu Jul 13 01:19:58 2023 +0530

    Added first commit

***path***/dummy-proj-for-git
