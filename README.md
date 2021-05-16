# HomeWork_23_new

https://github.com/netology-code/sysadm-homeworks/blob/master/02-git-03-branching/README.md

https://github.com/olegrovenskiy/HomeWork_23_new

icrosoft Windows [Version 10.0.19042.985]
(c) Корпорация Майкрософт (Microsoft Corporation). Все права защищены.

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_2_3>св юю
"св" не является внутренней или внешней
командой, исполняемой программой или пакетным файлом.

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_2_3>cd ..

(venv) C:\Users\Олег\PycharmProjects\New_Netology>git clone https://github.com/olegrovenskiy/HomeWork_23_new
Cloning into 'HomeWork_23_new'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

(venv) C:\Users\Олег\PycharmProjects\New_Netology>
(venv) C:\Users\Олег\PycharmProjects\New_Netology>cd HomeWork_23_new

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        branching/

nothing added to commit but untracked files present (use "git add" to track)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>cd branching

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new\branching>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ./

nothing added to commit but untracked files present (use "git add" to track)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new\branching>cd ..

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        branching/

nothing added to commit but untracked files present (use "git add" to track)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git add branching/merge.sh branching/rebase.sh
warning: LF will be replaced by CRLF in branching/merge.sh.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in branching/rebase.sh.
The file will have its original line endings in your working directory

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   branching/merge.sh
        new file:   branching/rebase.sh


(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git commit -m "prepare for merge and rebase"
[main ada9c4d] prepare for merge and rebase
 2 files changed, 16 insertions(+)
 create mode 100644 branching/merge.sh
 create mode 100644 branching/rebase.sh

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git log
commit ada9c4dbb7be7df117718ff388c17a506fba3fba (HEAD -> main)
Author: oleg.rovenskiy <roleg_n@mail.ru>
Date:   Sun May 16 21:49:12 2021 +0300

    prepare for merge and rebase

commit 047fb23e26049c32a6947af2e9d5ae890d1abba4 (origin/main, origin/HEAD)
Author: olegrovenskiy <83588609+olegrovenskiy@users.noreply.github.com>
Date:   Sun May 16 21:37:21 2021 +0300

    Initial commit

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git checkout -b git-merge
Switched to a new branch 'git-merge'

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git add branching/merge.sh
warning: LF will be replaced by CRLF in branching/merge.sh.
The file will have its original line endings in your working directory

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git commit -m "merge: @ instead"
[git-merge 58b9b49] merge: @ instead
 1 file changed, 2 insertions(+), 2 deletions(-)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git add branching/merge.sh
warning: LF will be replaced by CRLF in branching/merge.sh.
The file will have its original line endings in your working directory

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git commit -m "merge: use shift"
[git-merge e8b95d9] merge: use shift
 1 file changed, 3 insertions(+), 2 deletions(-)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git add branching/rebase.sh
warning: LF will be replaced by CRLF in branching/rebase.sh.
The file will have its original line endings in your working directory

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git commit -m "Change Main"
[main d14f941] Change Main
 1 file changed, 4 insertions(+), 2 deletions(-)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 830 bytes | 276.00 KiB/s, done.
Total 8 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/olegrovenskiy/HomeWork_23_new
   047fb23..d14f941  main -> main

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git checkout git-merge
Switched to branch 'git-merge'

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git push
fatal: The current branch git-merge has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin git-merge


(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git push origin git-merge
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 860 bytes | 286.00 KiB/s, done.
Total 8 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'git-merge' on GitHub by visiting:
remote:      https://github.com/olegrovenskiy/HomeWork_23_new/pull/new/git-merge
remote:
To https://github.com/olegrovenskiy/HomeWork_23_new
 * [new branch]      git-merge -> git-merge

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git log
commit e8b95d906d0fdf043a0b160fd21f5fea1d74ab44 (HEAD -> git-merge, origin/git-merge)
Author: oleg.rovenskiy <roleg_n@mail.ru>
Date:   Sun May 16 21:54:32 2021 +0300

    merge: use shift

commit 58b9b4963c9e5e1ef349bb55dc1c73c55c94e0af
Author: oleg.rovenskiy <roleg_n@mail.ru>
Date:   Sun May 16 21:53:30 2021 +0300

    merge: @ instead

commit ada9c4dbb7be7df117718ff388c17a506fba3fba
Author: oleg.rovenskiy <roleg_n@mail.ru>
Date:   Sun May 16 21:49:12 2021 +0300

    prepare for merge and rebase

commit 047fb23e26049c32a6947af2e9d5ae890d1abba4
Author: olegrovenskiy <83588609+olegrovenskiy@users.noreply.github.com>
Date:   Sun May 16 21:37:21 2021 +0300

    Initial commit

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git checkout ada9c4dbb7be7df117718ff388c17a506fba3fba
Note: switching to 'ada9c4dbb7be7df117718ff388c17a506fba3fba'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at ada9c4d prepare for merge and rebase

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git checkout -b git-rebase
Switched to a new branch 'git-rebase'

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git add branching/rebase.sh
warning: LF will be replaced by CRLF in branching/rebase.sh.
The file will have its original line endings in your working directory

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git commit -m "git-rebase1"
[git-rebase 029be4e] git-rebase1
 1 file changed, 4 insertions(+), 2 deletions(-)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git add branching/rebase.sh
warning: LF will be replaced by CRLF in branching/rebase.sh.
The file will have its original line endings in your working directory

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git commit -m "git-rebase2"
[git-rebase 1597f96] git-rebase2
 1 file changed, 2 insertions(+), 1 deletion(-)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git push origin git-rebase
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 811 bytes | 270.00 KiB/s, done.
Total 8 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'git-rebase' on GitHub by visiting:
remote:      https://github.com/olegrovenskiy/HomeWork_23_new/pull/new/git-rebase
remote:
To https://github.com/olegrovenskiy/HomeWork_23_new
 * [new branch]      git-rebase -> git-rebase

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>

Промежуточный итог

https://c2n.me/4c2JP8U.png

----------------

MERGE

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git merge git-merge
Merge made by the 'recursive' strategy.
 branching/merge.sh | 5 +++--
 1 file changed, 3 insertions(+), 2 deletions(-)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 390 bytes | 195.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/olegrovenskiy/HomeWork_23_new
   d14f941..5272729  main -> main

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>



https://c2n.me/4c2JUbQ.png

--------------

REBASE

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git checkout git-rebase
Switched to branch 'git-rebase'

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git rebase -i main
error: could not parse 'pick'
error: invalid line 2: fixup pick 1597f96 git-rebase2
You can fix this with 'git rebase --edit-todo' and then run 'git rebase --continue'.
Or you can abort the rebase with 'git rebase --abort'.

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git rebase --edit-todo
error: could not parse 'pick'
error: invalid line 2: fixup pick 1597f96 git-rebase2

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git rebase --continue
error: could not apply 029be4e... git-rebase1
Resolve all conflicts manually, mark them as resolved with
"git add/rm <conflicted_files>", then run "git rebase --continue".
You can instead skip this commit: run "git rebase --skip".
To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 029be4e... git-rebase1
Auto-merging branching/rebase.sh
CONFLICT (content): Merge conflict in branching/rebase.sh

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git add branching/rebase.sh
warning: LF will be replaced by CRLF in branching/rebase.sh.
The file will have its original line endings in your working directory

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git rebase --continue
[detached HEAD 354892d] git-rebase1
 1 file changed, 1 insertion(+)
error: could not apply 1597f96... git-rebase2
Resolve all conflicts manually, mark them as resolved with
"git add/rm <conflicted_files>", then run "git rebase --continue".
You can instead skip this commit: run "git rebase --skip".
To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 1597f96... git-rebase2
Auto-merging branching/rebase.sh
CONFLICT (content): Merge conflict in branching/rebase.sh

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git add branching/rebase.sh
warning: LF will be replaced by CRLF in branching/rebase.sh.
The file will have its original line endings in your working directory

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git rebase --continue
[detached HEAD b4893cc] Merge branch 'git-merge'
 Date: Sun May 16 22:04:26 2021 +0300
 1 file changed, 3 insertions(+), 1 deletion(-)
Successfully rebased and updated refs/heads/git-rebase.

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git push -u origin git-rebase
To https://github.com/olegrovenskiy/HomeWork_23_new
 ! [rejected]        git-rebase -> git-rebase (non-fast-forward)
error: failed to push some refs to 'https://github.com/olegrovenskiy/HomeWork_23_new'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git push -u origin git-rebase -f
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 425 bytes | 425.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/olegrovenskiy/HomeWork_23_new
 + 1597f96...b4893cc git-rebase -> git-rebase (forced update)
Branch 'git-rebase' set up to track remote branch 'git-rebase' from 'origin'.

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git merge git-rebase
Updating 5272729..b4893cc
Fast-forward
 branching/rebase.sh | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>
(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/olegrovenskiy/HomeWork_23_new
   5272729..b4893cc  main -> main

(venv) C:\Users\Олег\PycharmProjects\New_Netology\HomeWork_23_new>

https://c2n.me/4c2Kk7a.png






















