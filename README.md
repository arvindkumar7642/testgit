PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> & C:/Users/sdesa/AppData/Local/Programs/Python/Python312/python.exe c:/Users/sdesa/OneDrive/Desktop/test.py
helo world
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> python
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git config --global user.name "shiivam"
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git config --global user.name "samarth"
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git config --global user.email "sdesamaarth@gmail.com"      
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git config --global core.editor "code --wait"
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git init
Initialized empty Git repository in C:/Users/sdesa/OneDrive/Desktop/New folder (3)/.git/
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git add *.py
fatal: pathspec '*.py' did not match any files
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git add *.py
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git add *.js
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git commit -m "init: initial commit"
[master (root-commit) 4d8e8fa] init: initial commit
 2 files changed, 1 insertion(+)
 create mode 100644 abc.js
 create mode 100644 test.py
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git status
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    abc.js

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> 
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git commit -m "init: initial commit"
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    abc.js

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git add *.js
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git status  
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    abc.js

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git log
commit 4d8e8fa1f61fabe44bfc5f545aeb49ee90b142de (HEAD -> master)
Author: samarth <sdesamaarth@gmail.com>
Date:   Thu Dec 14 11:03:32 2023 +0530

    init: initial commit
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git config --global user.email "sdesamarth@gmail.com"  
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git log
commit 4d8e8fa1f61fabe44bfc5f545aeb49ee90b142de (HEAD -> master)
Author: samarth <sdesamaarth@gmail.com>
Date:   Thu Dec 14 11:03:32 2023 +0530

    init: initial commit
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> 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
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 : The term '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' is not 
recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the      
name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ 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
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (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:String) [], CommandNo  
   tFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git config --global user.email "sdesamarth@gmail.com"  
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git commit -m "init: initial commit"
[master 959a938] init: initial commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 abc.js
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git log
commit 959a938ff68562f79a1e32acf37fb8041fc06a7f (HEAD -> master)
Author: samarth <sdesamarth@gmail.com>
Date:   Thu Dec 14 11:20:37 2023 +0530

    init: initial commit

commit 4d8e8fa1f61fabe44bfc5f545aeb49ee90b142de
Author: samarth <sdesamaarth@gmail.com>
Date:   Thu Dec 14 11:03:32 2023 +0530

    init: initial commit
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> ls -a
Get-ChildItem : Parameter cannot be processed because the parameter name 'a' is ambiguous. Possible matches 
include: -Attributes -Directory -File -Hidden -ReadOnly -System.
At line:1 char:4
+ ls -a
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : AmbiguousParameter,Microsoft.PowerShell.Commands.GetChildItemCommand

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> ls


    Directory: C:\Users\sdesa\OneDrive\Desktop\New folder (3)


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        14-12-2023  10:45 AM             19 test.py


PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git remote add "samarth"
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git remote add origin https://github.com/sdesamarth/testgit.git 
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git remote -v 
origin  https://github.com/sdesamarth/testgit.git (fetch)
origin  https://github.com/sdesamarth/testgit.git (push)
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git remote -v
origin  https://github.com/sdesamarth/testgit.git (fetch)
origin  https://github.com/sdesamarth/testgit.git (push)
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git remote add origin https://github.com/sdesamarth/testgit.git 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
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git remote add -origin https://sdesamarth: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@github.com/sdesamarth/testgit.git        
error: unknown switch `o'
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git remote -v
origin  https://github.com/sdesamarth/testgit.git (fetch)
origin  https://github.com/sdesamarth/testgit.git (push)
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git commit
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        abc.js

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git branch
* master
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git branch -m main
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git branch -M main
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git branch
* main
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git push origin main
info: please complete authentication in your browser...
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git push origin main
info: please complete authentication in your browser...
To https://github.com/sdesamarth/testgit.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/sdesamarth/testgit.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git push origin main
To https://github.com/sdesamarth/testgit.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/sdesamarth/testgit.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 594 bytes | 45.00 KiB/s, done.
From https://github.com/sdesamarth/testgit
 * [new branch]      main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git push origin main
To https://github.com/sdesamarth/testgit.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/sdesamarth/testgit.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git push --set-upstream origin main
To https://github.com/sdesamarth/testgit.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/sdesamarth/testgit.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git pull --rebase
>>
There is no tracking information for the current branch.
Please specify which branch you want to rebase against.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git pull --rebase
There is no tracking information for the current branch.
Please specify which branch you want to rebase against.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git push origin FixForBug
error: src refspec FixForBug does not match any
error: failed to push some refs to 'https://github.com/sdesamarth/testgit.git'
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git remote -v
origin  https://github.com/sdesamarth/testgit.git (fetch)
origin  https://github.com/sdesamarth/testgit.git (push)
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git pull --rebase origin main
From https://github.com/sdesamarth/testgit
 * branch            main       -> FETCH_HEAD
error: The following untracked working tree files would be overwritten by merge:
        abc.js
Please move or remove them before you merge.
Aborting
hint: Could not execute the todo command
hint:
hint:     pick 4d8e8fa1f61fabe44bfc5f545aeb49ee90b142de init: initial commit
hint:
hint: It has been rescheduled; To edit the command before continuing, please
hint: edit the todo list first:
hint:
hint:     git rebase --edit-todo
hint:     git rebase --continue
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git push origin main
>>
To https://github.com/sdesamarth/testgit.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/sdesamarth/testgit.git'
hint: Updates were rejected because a pushed branch tip is behind its remote
hint: counterpart. If you want to integrate the remote changes, use 'git pull'
hint: before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> git push origin main
To https://github.com/sdesamarth/testgit.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/sdesamarth/testgit.git'
hint: Updates were rejected because a pushed branch tip is behind its remote
hint: counterpart. If you want to integrate the remote changes, use 'git pull'
hint: before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\sdesa\OneDrive\Desktop\New folder (3)> 
