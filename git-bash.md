**path**/GIT
git --version
git version 2.38.1.windows.1

**path**/GIT
mkdir dummy-proj-for-git

**path**/GIT
cd dummy-proj-for-git/

C:/Users/Epitome/Desktop/BACKEND/GIT/dummy-proj-for-git/.git/

**path**/GIT/dummy-proj-for-git
ls

**path**/GIT/dummy-proj-for-git
ls -a
sktop/BACKEND/GIT/dummy-proj-for-git
git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

**path**/GIT/dummy-proj-for-git
touch index.js

**path**/GIT/dummy-proj-for-git
cat index.js
console.log("Hello from git");

**path**/GIT/dummy-proj-for-git
git status
On branch master

No commits yet

Untracked files:
(use "git add <file>..." to include in what will be committed) git-Command.md
index.js

nothing added to commit but untracked files present (use "git add" to track)

**path**/GIT/dummy-proj-for-git
git remote

**path**/GIT/dummy-proj-for-git
git add index.js

**path**/GIT/dummy-proj-for-git
git status
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)
new file: index.js

Untracked files:
(use "git add <file>..." to include in what will be committed) git-Command.md

**path**/GIT/dummy-proj-for-git
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

**path**/GIT/dummy-proj-for-git
git commit -m "Added first commit"
[master (root-commit) 4d99528] Added first commit
1 file changed, 1 insertion(+)
create mode 100644 index.js

**path**/GIT/dummy-proj-for-git
git log
commit 4d99528c62287ef212baddf53667a59f633847ae (HEAD -> master)Author: Adarsh <**sec**adarsh@gmail.com>
Date: Thu Jul 13 01:19:58 2023 +0530

    Added first commit

**path**/GIT/dummy-proj-for-git
git status
On branch master
Changes not staged for commit:
(use "git add <file>..." to update what will be committed)  
 (use "git restore <file>..." to discard changes in working directory)
modified: index.js

Untracked files:
(use "git add <file>..." to include in what will be committed) git-Command.md

no changes added to commit (use "git add" and/or "git commit -a")

**path**/GIT/dummy-proj-for-git
git add .

**path**/GIT/dummy-proj-for-git
git status
On branch master
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: git-Command.md
modified: index.js

**path**/GIT/dummy-proj-for-git
git commit -m "Git commands added"
[master d1f965f] Git commands added
2 files changed, 81 insertions(+), 1 deletion(-)
create mode 100644 git-Command.md

**path**/GIT/dummy-proj-for-git
git log
commit d1f965f5c6d0e2c866e761ce6e16098233938119 (HEAD -> master)Author: Adarsh <**sec**adarsh@gmail.com>
Date: Thu Jul 13 01:28:51 2023 +0530

    Git commands added

commit 4d99528c62287ef212baddf53667a59f633847ae
Author: Adarsh <**sec**adarsh@gmail.com>
Date: Thu Jul 13 01:19:58 2023 +0530

    Added first commit

**path**/GIT/dummy-proj-for-git
^C

**path**/GIT/dummy-proj-for-git
^C

**path**/GIT/dummy-proj-for-git
^C

**path**/GIT/dummy-proj-for-git
^C

**path**/GIT/dummy-proj-for-git

**path**/GIT/dummy-proj-for-git

**path**/GIT/dummy-proj-for-git

**path**/GIT/dummy-proj-for-git

**path**/GIT/dummy-proj-for-git
git add .

**path**/GIT/dummy-proj

**path**/GIT/dummy-proj-for-git
git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

**path**/GIT/dummy-proj-for-git
git remote add origin https://github.com/callbackhell-1/GIT-Project.git

**path**/GIT/dummy-proj-for-git
git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/callbackhell-1/GIT-Project.git'

**path**/GIT/dummy-proj-for-git
git branch

- master

**path**/GIT/dummy-proj-for-git
git push origin master
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (10/10), 2.92 KiB | 31.00 KiB/s, done.
Total 10 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/callbackhell-1/GIT-Project.git

- [new branch] master -> master

**path**/GIT/dummy-proj-for-git
git add .

**path**/GIT/dummy-proj-for-git
git status
On branch master
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
modified: git-Command.md
modified: git-bash.md

**path**/GIT/dummy-proj-for-git
