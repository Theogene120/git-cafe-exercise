# git-cafe-exercise

# Bundle-5

## Exercise-2

```bash

user@LAPTOP-GQ4K54L5 MINGW64 ~
$ git clone https://github.com/Theogene120/git-cafe-exercise
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 92 (from 1)
Receiving objects: 100% (107/107), 1.95 MiB | 1.00 MiB/s, done.
Resolving deltas: 100% (5/5), done.

user@LAPTOP-GQ4K54L5 MINGW64 ~
$ cd git-cafe-exercise

user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (main)
$ code .

user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (main)
$ git add index.html

user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (main)
$ git commit -m "Place changed to Restaurant"
[main 1eab047] Place changed to Restaurant
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Theogene120/git-cafe-exercise
   d1d3f9c..1eab047  main -> main
```
# Bundle-6 

## Exercise-1

```bash

user@LAPTOP-GQ4K54L5 MINGW64 ~
$ cd git-cafe-exercise

user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (main)
$ git checkout -b new-feature
Switched to a new branch 'new-feature'

user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (new-feature)
$ echo > menu.html

user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (new-feature)
$ git add menu.html
warning: in the working copy of 'menu.html', LF will be replaced by CRLF the next time Git touches it

user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (new-feature)
$ git commit -m "Menu file has been added to project"
[new-feature 286eecc] Menu file has been added to project
 1 file changed, 47 insertions(+)
 create mode 100644 menu.html

user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (new-feature)
$ git push
fatal: The current branch new-feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin new-feature

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@LAPTOP-GQ4K54L5 MINGW64 ~/git-cafe-exercise (new-feature)
$ git push --set-upstream origin new-feature
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 543 bytes | 271.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'new-feature' on GitHub by visiting:
remote:      https://github.com/Theogene120/git-cafe-exercise/pull/new/new-feature
remote:
To https://github.com/Theogene120/git-cafe-exercise
 * [new branch]      new-feature -> new-feature
branch 'new-feature' set up to track 'origin/new-feature'.

```