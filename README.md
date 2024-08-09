B - <git add .\arquivo.txt> , <git status>; 

PS S:\Projetos\exercicio01> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file:   arquivo.txt

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   README.md

Untracked files:
(use "git add <file>..." to include in what will be committed)
.idea/

C - <git commit -m "git add example - arquivo.txt">;

PS S:\Projetos\exercicio01> git commit -m "git add example - arquivo.txt"
[main deeadfd] git add example - arquivo.txt
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 arquivo.txt


E - <git diff arquivo.txt>; 

$ git diff arquivo.txt
diff --git a/arquivo.txt b/arquivo.txt
index d789aa4..420e05c 100644
Binary files a/arquivo.txt and b/arquivo.txt differ

F - <git add arquivo.txt> , <git status>; 

On branch main
Your branch is ahead of 'origin/main' by 1 commit.
(use "git push" to publish your local commits)

Changes to be committed:
(use "git restore --staged <file>..." to unstage)
modified:   arquivo.txt

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   README.md

Untracked files:
(use "git add <file>..." to include in what will be committed)
.idea/

G - <git diff --staged>; 

diff --git a/arquivo.txt b/arquivo.txt
index d789aa4..420e05c 100644
Binary files a/arquivo.txt and b/arquivo.txt differ

I - <git diff arquivo.txt>

warning: in the working copy of 'arquivo.txt', LF will be replaced by CRLF the next time Git touches it
diff --git a/arquivo.txt b/arquivo.txt
index 420e05c..75016ea 100644
Binary files a/arquivo.txt and b/arquivo.txt differ

J - <git restore arquivo.txt>, <git status>;

On branch main
Your branch is ahead of 'origin/main' by 1 commit.
(use "git push" to publish your local commits)

Changes to be committed:
(use "git restore --staged <file>..." to unstage)
modified:   arquivo.txt

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   README.md

Untracked files:
(use "git add <file>..." to include in what will be committed)
.gitignore

K - <git commit -m "exercicio k">, <git log>;

[main 9821742] exercicio k
1 file changed, 0 insertions(+), 0 deletions(-)

commit 9821742bc34e1c2dbb298928b8de037f390eaa79 (HEAD -> main)
Author: Willy Catão <50681413+wscatao@users.noreply.github.com>
Date:   Fri Aug 9 09:31:12 2024 -0300

    exercicio k

commit deeadfdcd7f9e33551980892cdec7bb34226697c
Author: Willy Catão <50681413+wscatao@users.noreply.github.com>
Date:   Thu Aug 8 22:34:23 2024 -0300

    git add example - arquivo.txt

commit ad6b44a92ca79f657df7d420a8d02ebc6bd8df03 (origin/main, origin/HEAD)
Author: Willy Catão <50681413+wscatao@users.noreply.github.com>
Date:   Thu Aug 8 22:22:43 2024 -0300

    Create README.md

 M - <git status>;

$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
(use "git push" to publish your local commits)

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   README.md

Untracked files:
(use "git add <file>..." to include in what will be committed)
.gitignore

no changes added to commit (use "git add" and/or "git commit -a")





