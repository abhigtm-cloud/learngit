 The file format is 'md', which stands for Markdown documentation. It is a lightweight markup language that can be easily converted to text.

 Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\Users\abhig> cd..
PS C:\Users> cd..
PS C:\> cd learngit
PS C:\learngit> cd one4
cd : Cannot find path 'C:\learngit\one4' because it does not exist.
At line:1 char:1
+ cd one4
+ ~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\learngit\one4:String) [Set-Location], ItemNotFound
   Exception
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\learngit> cd one
PS C:\learngit\one> git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   file1.txt

PS C:\learngit\one> cd one
cd : Cannot find path 'C:\learngit\one\one' because it does not exist.
At line:1 char:1
+ cd one
+ ~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\learngit\one\one:String) [Set-Location], ItemNotFo
   undException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\learngit\one> git diff --staged
diff --git a/file1.txt b/file1.txt
index f61e678..86cb4cd 100644
--- a/file1.txt
+++ b/file1.txt
@@ -1,2 +1,4 @@
 and my surname is gautam and my passion is clicking photographs
 hi this is my first file and my name is abhinav and i love reading books
+abhinav
+abhinav
\ No newline at end of file
PS C:\learngit\one> git diff master bug-fix
diff --git a/file1.txt b/file1.txt
index f61e678..e620ab3 100644
--- a/file1.txt
+++ b/file1.txt
@@ -1,2 +1,4 @@
-and my surname is gautam and my passion is clicking photographs
 hi this is my first file and my name is abhinav and i love reading books
+hi this is my first file and my name is abhinav and i love reading books
+and hola amigo
+and my surname is gautam and my passion is clicking photographs
PS C:\learngit\one> git log
commit d49dd88ae1360a3b37a3f79848fa0e7ea8045d2b (HEAD -> master)
commit d49dd88ae1360a3b37a3f79848fa0e7ea8045d2b (HEAD -> master)
Merge: 2e53998 6d51f18
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:31:11 2025 +0530

    conflict resolved

commit 2e539989cd3459e1c64f76deb8cebc7d1d239f24
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:29:20 2025 +0530

    added passion

commit 9e87183bc92db2d7be1a169968ef6faf7c37d5bb
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:28:53 2025 +0530

    added sur-name

commit 6d51f188f0d35b90775d004e9ee6a9174a154a42
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:46 2025 +0530

    added hobby

commit 689bfc0f6c219e6a7bf8d3afa157059eab743173
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:23 2025 +0530

    added name

commit 996320a7feacbe2897fae99a78d0b3a38aeb77dc
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:02:25 2025 +0530

    changed file

commit 86fd17c4368cc5f32b246337f71c36dc76631fe3
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:33:29 2025 +0530

    added two filea

commit 0c46443cbe2746a4440024b3c40621446c9daff1
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:27:10 2025 +0530

    changed some changes

commit 655e175e47318d627b27088b26906fcb863b53be
:
commit d49dd88ae1360a3b37a3f79848fa0e7ea8045d2b (HEAD -> master)
Merge: 2e53998 6d51f18
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:31:11 2025 +0530

    conflict resolved

commit 2e539989cd3459e1c64f76deb8cebc7d1d239f24
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:29:20 2025 +0530

    added passion

commit 9e87183bc92db2d7be1a169968ef6faf7c37d5bb
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:28:53 2025 +0530

    added sur-name

commit 6d51f188f0d35b90775d004e9ee6a9174a154a42
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:46 2025 +0530

    added hobby

commit 689bfc0f6c219e6a7bf8d3afa157059eab743173
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:23 2025 +0530

    added name

commit 996320a7feacbe2897fae99a78d0b3a38aeb77dc
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:02:25 2025 +0530

    changed file

commit 86fd17c4368cc5f32b246337f71c36dc76631fe3
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:33:29 2025 +0530

    added two filea

commit 0c46443cbe2746a4440024b3c40621446c9daff1
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:27:10 2025 +0530

    changed some changes

commit 655e175e47318d627b27088b26906fcb863b53be
:
commit d49dd88ae1360a3b37a3f79848fa0e7ea8045d2b (HEAD -> master)
Merge: 2e53998 6d51f18
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:31:11 2025 +0530

commit d49dd88ae1360a3b37a3f79848fa0e7ea8045d2b (HEAD -> master)
Merge: 2e53998 6d51f18
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:31:11 2025 +0530

    conflict resolved

commit 2e539989cd3459e1c64f76deb8cebc7d1d239f24
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:29:20 2025 +0530

    added passion

commit 9e87183bc92db2d7be1a169968ef6faf7c37d5bb
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:28:53 2025 +0530

    added sur-name

commit 6d51f188f0d35b90775d004e9ee6a9174a154a42
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:46 2025 +0530

    added hobby

commit 689bfc0f6c219e6a7bf8d3afa157059eab743173
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:23 2025 +0530

    added name

commit 996320a7feacbe2897fae99a78d0b3a38aeb77dc
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:02:25 2025 +0530

    changed file

commit 86fd17c4368cc5f32b246337f71c36dc76631fe3
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:33:29 2025 +0530

    added two filea

commit 0c46443cbe2746a4440024b3c40621446c9daff1
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:27:10 2025 +0530

    changed some changes

commit 655e175e47318d627b27088b26906fcb863b53be
...skipping...

                   SUMMARY OF LESS COMMANDS

      Commands marked with * may be preceded by a number, N.
      Notes in parentheses indicate the behavior if N is given.
      A key preceded by a caret indicates the Ctrl key; thus ^K is ctrl-K.

  h  H                 Display this help.
  q  :q  Q  :Q  ZZ     Exit.
 ---------------------------------------------------------------------------

                           MOVING

  e  ^E  j  ^N  CR  *  Forward  one line   (or N lines).
  y  ^Y  k  ^K  ^P  *  Backward one line   (or N lines).
  f  ^F  ^V  SPACE  *  Forward  one window (or N lines).
  b  ^B  ESC-v      *  Backward one window (or N lines).
  z                 *  Forward  one window (and set window to N).
  w                 *  Backward one window (and set window to N).
  ESC-SPACE         *  Forward  one window, but don't stop at end-of-file.
  d  ^D             *  Forward  one half-window (and set half-window to N).
  u  ^U             *  Backward one half-window (and set half-window to N).
  ESC-)  RightArrow *  Right one half screen width (or N positions).
  ESC-(  LeftArrow  *  Left  one half screen width (or N positions).
  ESC-}  ^RightArrow   Right to last column displayed.
  ESC-{  ^LeftArrow    Left  to first column.
  F                    Forward forever; like "tail -f".
  ESC-F                Like F but stop when search pattern is found.
  r  ^R  ^L            Repaint screen.
  R                    Repaint screen, discarding buffered input.
        ---------------------------------------------------
        Default "window" is the screen height.
        Default "half-window" is half of the screen height.
 ---------------------------------------------------------------------------

                          SEARCHING

  /pattern          *  Search forward for (N-th) matching line.
  ?pattern          *  Search backward for (N-th) matching line.
  n                 *  Repeat previous search (for N-th occurrence).
  N                 *  Repeat previous search in reverse direction.
  ESC-n             *  Repeat previous search, spanning files.
  ESC-N             *  Repeat previous search, reverse dir. & spanning files.
  ^O^N  ^On         *  Search forward for (N-th) OSC8 hyperlink.
  ^O^P  ^Op         *  Search backward for (N-th) OSC8 hyperlink.
  ^O^L  ^Ol            Jump to the currently selected OSC8 hyperlink.
  ESC-u                Undo (toggle) search highlighting.
  ESC-U                Clear search highlighting.
  &pattern          *  Display only matching lines.
        ---------------------------------------------------
HELP -- Press RETURN for more, or q when done...skipping...
commit d49dd88ae1360a3b37a3f79848fa0e7ea8045d2b (HEAD -> master)
Merge: 2e53998 6d51f18
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:31:11 2025 +0530

    conflict resolved

commit 2e539989cd3459e1c64f76deb8cebc7d1d239f24
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:29:20 2025 +0530

    added passion

commit 9e87183bc92db2d7be1a169968ef6faf7c37d5bb
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:28:53 2025 +0530

    added sur-name

commit 6d51f188f0d35b90775d004e9ee6a9174a154a42
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:46 2025 +0530

    added hobby

commit 689bfc0f6c219e6a7bf8d3afa157059eab743173
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:23 2025 +0530

    added name

commit 996320a7feacbe2897fae99a78d0b3a38aeb77dc
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:02:25 2025 +0530

    changed file

commit 86fd17c4368cc5f32b246337f71c36dc76631fe3
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:33:29 2025 +0530

    added two filea

commit 0c46443cbe2746a4440024b3c40621446c9daff1
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:27:10 2025 +0530

    changed some changes

commit 655e175e47318d627b27088b26906fcb863b53be
...skipping...

                   SUMMARY OF LESS COMMANDS

      Commands marked with * may be preceded by a number, N.
      Notes in parentheses indicate the behavior if N is given.
      A key preceded by a caret indicates the Ctrl key; thus ^K is ctrl-K.

  h  H                 Display this help.
  q  :q  Q  :Q  ZZ     Exit.
 ---------------------------------------------------------------------------

                           MOVING

  e  ^E  j  ^N  CR  *  Forward  one line   (or N lines).
  y  ^Y  k  ^K  ^P  *  Backward one line   (or N lines).
  f  ^F  ^V  SPACE  *  Forward  one window (or N lines).
  b  ^B  ESC-v      *  Backward one window (or N lines).
  z                 *  Forward  one window (and set window to N).
  w                 *  Backward one window (and set window to N).
  ESC-SPACE         *  Forward  one window, but don't stop at end-of-file.
  d  ^D             *  Forward  one half-window (and set half-window to N).
  u  ^U             *  Backward one half-window (and set half-window to N).
  ESC-)  RightArrow *  Right one half screen width (or N positions).
  ESC-(  LeftArrow  *  Left  one half screen width (or N positions).
  ESC-}  ^RightArrow   Right to last column displayed.
  ESC-{  ^LeftArrow    Left  to first column.
  F                    Forward forever; like "tail -f".
  ESC-F                Like F but stop when search pattern is found.
  r  ^R  ^L            Repaint screen.
  R                    Repaint screen, discarding buffered input.
        ---------------------------------------------------
        Default "window" is the screen height.
        Default "half-window" is half of the screen height.
 ---------------------------------------------------------------------------

                          SEARCHING

  /pattern          *  Search forward for (N-th) matching line.
  ?pattern          *  Search backward for (N-th) matching line.
  n                 *  Repeat previous search (for N-th occurrence).
  N                 *  Repeat previous search in reverse direction.
  ESC-n             *  Repeat previous search, spanning files.
  ESC-N             *  Repeat previous search, reverse dir. & spanning files.
  ^O^N  ^On         *  Search forward for (N-th) OSC8 hyperlink.
  ^O^P  ^Op         *  Search backward for (N-th) OSC8 hyperlink.
  ^O^L  ^Ol            Jump to the currently selected OSC8 hyperlink.
  ESC-u                Undo (toggle) search highlighting.
  ESC-U                Clear search highlighting.
  &pattern          *  Display only matching lines.
        ---------------------------------------------------
HELP -- Press RETURN for more, or q when done...skipping...
commit d49dd88ae1360a3b37a3f79848fa0e7ea8045d2b (HEAD -> master)
Merge: 2e53998 6d51f18
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:31:11 2025 +0530

    conflict resolved

commit 2e539989cd3459e1c64f76deb8cebc7d1d239f24
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:29:20 2025 +0530

    added passion

commit 9e87183bc92db2d7be1a169968ef6faf7c37d5bb
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:28:53 2025 +0530

    added sur-name

commit 6d51f188f0d35b90775d004e9ee6a9174a154a42
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:46 2025 +0530

    added hobby

commit 689bfc0f6c219e6a7bf8d3afa157059eab743173
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:23 2025 +0530

    added name

commit 996320a7feacbe2897fae99a78d0b3a38aeb77dc
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:02:25 2025 +0530

    changed file

commit 86fd17c4368cc5f32b246337f71c36dc76631fe3
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:33:29 2025 +0530

    added two filea

commit 0c46443cbe2746a4440024b3c40621446c9daff1
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:27:10 2025 +0530

    changed some changes

commit 655e175e47318d627b27088b26906fcb863b53be
PS C:\learngit\one> git log -oneline
fatal: unrecognized argument: -oneline
PS C:\learngit\one> git log --oneline
d49dd88 (HEAD -> master) conflict resolved
2e53998 added passion
9e87183 added sur-name
6d51f18 added hobby
689bfc0 added name
996320a changed file
86fd17c added two filea
0c46443 changed some changes
655e175 changed username and email
13aafcb updated the file2.txt
1038aa4 commited the files of one folder in the repo
PS C:\learngit\one> git diff d49dd88..6d51f18
diff --git a/file1.txt b/file1.txt
index f61e678..adb8995 100644
--- a/file1.txt
+++ b/file1.txt
@@ -1,2 +1 @@
-and my surname is gautam and my passion is clicking photographs
-hi this is my first file and my name is abhinav and i love reading books
+hi this is my first file and my name is abhinav and i love reading books
\ No newline at end of file
PS C:\learngit\one> git checkout bugfix;
error: pathspec 'bugfix' did not match any file(s) known to git
PS C:\learngit\one> git checkout bugfix
error: pathspec 'bugfix' did not match any file(s) known to git
PS C:\learngit\one> git checkout bug-fix
error: Your local changes to the following files would be overwritten by checkout:
        file1.txt
Please commit your changes or stash them before you switch branches.
Aborting
PS C:\learngit\one> git stash
Saved working directory and index state WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git checkout bug-fix
Switched to branch 'bug-fix'
PS C:\learngit\one> git checkout master
Switched to branch 'master'
PS C:\learngit\one> git stash list
stash@{0}: WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git stash apply
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git checkout master
M       file1.txt
Already on 'master'
PS C:\learngit\one> git stash apply
error: Your local changes to the following files would be overwritten by merge:
        file1.txt
Please commit your changes or stash them before you merge.
Aborting
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git checkout bug-fix
error: Your local changes to the following files would be overwritten by checkout:
        file1.txt
Please commit your changes or stash them before you switch branches.
Aborting
PS C:\learngit\one> git stash
Saved working directory and index state WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git checkout bug-fix
Switched to branch 'bug-fix'
PS C:\learngit\one> git stash apply
Auto-merging file1.txt
CONFLICT (content): Merge conflict in file1.txt
On branch bug-fix
Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git checkout master
file1.txt: needs merge
error: you need to resolve your current index first
PS C:\learngit\one> git status
On branch bug-fix
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   file1.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt

PS C:\learngit\one> git stash
Saved working directory and index state WIP on bug-fix: 2b5768c merge branches sccessfully
PS C:\learngit\one> git stash list
stash@{0}: WIP on bug-fix: 2b5768c merge branches sccessfully
stash@{1}: WIP on master: d49dd88 conflict resolved
stash@{2}: WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git stash apply stash@{0}
error: unknown switch `e'
usage: git stash apply [--index] [-q | --quiet] [<stash>]

    -q, --[no-]quiet      be quiet, only report errors
    --[no-]index          attempt to recreate the index

PS C:\learngit\one> git stash apply stash@{2}
error: unknown switch `e'
usage: git stash apply [--index] [-q | --quiet] [<stash>]

    -q, --[no-]quiet      be quiet, only report errors
    --[no-]index          attempt to recreate the index

PS C:\learngit\one> git stash list
stash@{0}: WIP on bug-fix: 2b5768c merge branches sccessfully
stash@{1}: WIP on master: d49dd88 conflict resolved
stash@{2}: WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git status
On branch bug-fix
nothing to commit, working tree clean
PS C:\learngit\one> git stash apply
error: Your local changes to the following files would be overwritten by merge:
        file1.txt
Please commit your changes or stash them before you merge.
Aborting
On branch bug-fix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add .
PS C:\learngit\one> git status
On branch bug-fix
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   file1.txt

PS C:\learngit\one> git stash
Saved working directory and index state WIP on bug-fix: 2b5768c merge branches sccessfully
PS C:\learngit\one> git stash list
stash@{0}: WIP on bug-fix: 2b5768c merge branches sccessfully
stash@{1}: WIP on bug-fix: 2b5768c merge branches sccessfully
stash@{2}: WIP on master: d49dd88 conflict resolved
stash@{3}: WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git stash apply stash@{0};
error: unknown switch `e'
usage: git stash apply [--index] [-q | --quiet] [<stash>]

    -q, --[no-]quiet      be quiet, only report errors
    --[no-]index          attempt to recreate the index

PS C:\learngit\one> git stash apply stash@{0}
error: unknown switch `e'
usage: git stash apply [--index] [-q | --quiet] [<stash>]

    -q, --[no-]quiet      be quiet, only report errors
    --[no-]index          attempt to recreate the index

PS C:\learngit\one> git stash apply stash@{0} bug-fix
error: unknown switch `e'
usage: git stash apply [--index] [-q | --quiet] [<stash>]

    -q, --[no-]quiet      be quiet, only report errors
    --[no-]index          attempt to recreate the index

PS C:\learngit\one> git status
On branch bug-fix
nothing to commit, working tree clean
PS C:\learngit\one> git stash apply
On branch bug-fix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git stash apply
error: Your local changes to the following files would be overwritten by merge:
        file1.txt
Please commit your changes or stash them before you merge.
Aborting
On branch bug-fix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git stash apply
error: Your local changes to the following files would be overwritten by merge:
        file1.txt
Please commit your changes or stash them before you merge.
Aborting
On branch bug-fix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git commit -m "abhi"
On branch bug-fix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add
PS C:\learngit\one> git add .
PS C:\learngit\one> git commit -m "abhi"
[bug-fix 9cf2e0c] abhi
 1 file changed, 1 insertion(+)
PS C:\learngit\one> git status
On branch bug-fix
nothing to commit, working tree clean
PS C:\learngit\one> git stash apply
On branch bug-fix
nothing to commit, working tree clean
PS C:\learngit\one> git log --oneline
d49dd88 (HEAD -> master) conflict resolved
2e53998 added passion
9e87183 added sur-name
6d51f18 added hobby
689bfc0 added name
996320a changed file
86fd17c added two filea
0c46443 changed some changes
655e175 changed username and email
13aafcb updated the file2.txt
1038aa4 commited the files of one folder in the repo
PS C:\learngit\one> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file2.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add .
PS C:\learngit\one> git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   file2.txt

PS C:\learngit\one> git stash
Saved working directory and index state WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file2.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add .
PS C:\learngit\one> git stash
Saved working directory and index state WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git stash list
stash@{0}: WIP on master: d49dd88 conflict resolved
stash@{1}: WIP on master: d49dd88 conflict resolved
stash@{2}: WIP on bug-fix: 2b5768c merge branches sccessfully
stash@{3}: WIP on bug-fix: 2b5768c merge branches sccessfully
stash@{4}: WIP on master: d49dd88 conflict resolved
stash@{5}: WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git stash apply stash@{0}
error: unknown switch `e'
usage: git stash apply [--index] [-q | --quiet] [<stash>]

    -q, --[no-]quiet      be quiet, only report errors
    --[no-]index          attempt to recreate the index

PS C:\learngit\one>
PS C:\learngit\one> git stash clear
PS C:\learngit\one> git stash list
PS C:\learngit\one> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file2.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add file2.txt
PS C:\learngit\one> git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   file2.txt

PS C:\learngit\one> git stash
Saved working directory and index state WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file2.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add file2.txt
PS C:\learngit\one> git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   file2.txt

PS C:\learngit\one> git stash
Saved working directory and index state WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git stash list
stash@{0}: WIP on master: d49dd88 conflict resolved
stash@{1}: WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git stash apply stash@{1}
error: unknown switch `e'
usage: git stash apply [--index] [-q | --quiet] [<stash>]

    -q, --[no-]quiet      be quiet, only report errors
    --[no-]index          attempt to recreate the index

PS C:\learngit\one> git log
commit d49dd88ae1360a3b37a3f79848fa0e7ea8045d2b (HEAD -> master)
Merge: 2e53998 6d51f18
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:31:11 2025 +0530

    conflict resolved

commit 2e539989cd3459e1c64f76deb8cebc7d1d239f24
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:29:20 2025 +0530

    added passion

commit 9e87183bc92db2d7be1a169968ef6faf7c37d5bb
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:28:53 2025 +0530

    added sur-name

commit 6d51f188f0d35b90775d004e9ee6a9174a154a42
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:46 2025 +0530

    added hobby

commit 689bfc0f6c219e6a7bf8d3afa157059eab743173
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:27:23 2025 +0530

    added name

commit 996320a7feacbe2897fae99a78d0b3a38aeb77dc
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 22:02:25 2025 +0530

    changed file

commit 86fd17c4368cc5f32b246337f71c36dc76631fe3
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:33:29 2025 +0530

    added two filea

commit 0c46443cbe2746a4440024b3c40621446c9daff1
Author: abhi <abhi1@gmail.com>
Date:   Sun Apr 6 12:27:10 2025 +0530

PS C:\learngit\one> git stash apply
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file2.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git stash drop stash@{0}
error: unknown switch `e'
usage: git stash drop [-q | --quiet] [<stash>]

    -q, --[no-]quiet      be quiet, only report errors

PS C:\learngit\one> git stash drop
Dropped refs/stash@{0} (844668d5287165727a7484a8b9d2691c57df2774)
PS C:\learngit\one> git stash list
stash@{0}: WIP on master: d49dd88 conflict resolved
PS C:\learngit\one> git stash apply
error: Your local changes to the following files would be overwritten by merge:
        file2.txt
Please commit your changes or stash them before you merge.
Aborting
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file2.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git tag abhi
PS C:\learngit\one> git tag
abhi
PS C:\learngit\one> git tag -a abhi1 -m "added abhi tag"
PS C:\learngit\one> git tag
abhi
abhi1
PS C:\learngit\one> git log --oneline
d49dd88 (HEAD -> master, tag: abhi1, tag: abhi) conflict resolved
2e53998 added passion
9e87183 added sur-name
6d51f18 added hobby
689bfc0 added name
996320a changed file
86fd17c added two filea
0c46443 changed some changes
655e175 changed username and email
13aafcb updated the file2.txt
1038aa4 commited the files of one folder in the repo
PS C:\learngit\one> git tag abhi2 d49dd88
PS C:\learngit\one> git tag
abhi
abhi1
abhi2
PS C:\learngit\one> git branch
  bug-fix
* master
  seconf-branch
PS C:\learngit\one> git switch -c pinkmode
Switched to a new branch 'pinkmode'
PS C:\learngit\one> git branch
  bug-fix
  master
* pinkmode
  seconf-branch
PS C:\learngit\one> git status
On branch pinkmode
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file2.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        pink.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add .
PS C:\learngit\one> git commit -m "add pink mode"
[pinkmode 767f8e9] add pink mode
 2 files changed, 3 insertions(+), 1 deletion(-)
 create mode 100644 pink.txt
PS C:\learngit\one> git checkout master
Switched to branch 'master'
PS C:\learngit\one> git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        pink.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\learngit\one> git add pink.txt
PS C:\learngit\one> git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   pink.txt

PS C:\learngit\one> git commit -m "checked pink mode"
[master 441f8f5] checked pink mode
 1 file changed, 3 insertions(+)
 create mode 100644 pink.txt
PS C:\learngit\one> git status
On branch master
nothing to commit, working tree clean
PS C:\learngit\one> git checkout pinkmode
Switched to branch 'pinkmode'
PS C:\learngit\one> git merge master
Auto-merging pink.txt
CONFLICT (add/add): Merge conflict in pink.txt
Automatic merge failed; fix conflicts and then commit the result.
PS C:\learngit\one> git merge master
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
PS C:\learngit\one> git branch
  bug-fix
  master
* pinkmode
  seconf-branch
PS C:\learngit\one> git merge master
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
PS C:\learngit\one> git status
On branch pinkmode
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both added:      pink.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add .
PS C:\learngit\one> git commit -m "added"
[pinkmode c574e27] added
PS C:\learngit\one> git status
On branch pinkmode
nothing to commit, working tree clean
PS C:\learngit\one> git merge master
Already up to date.
PS C:\learngit\one> git status
On branch pinkmode
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pink.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add pink.txt
PS C:\learngit\one> git commit -m "added abhii"
[pinkmode 6cb91ef] added abhii
 1 file changed, 2 insertions(+)
PS C:\learngit\one> git checkout master
Switched to branch 'master'
PS C:\learngit\one> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pink.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add pink.txt
PS C:\learngit\one> git commit -m "added gautam"
[master a9bb708] added gautam
 1 file changed, 1 insertion(+), 3 deletions(-)
PS C:\learngit\one> git status
On branch master
nothing to commit, working tree clean
PS C:\learngit\one> git checkout pinkmode
Switched to branch 'pinkmode'
PS C:\learngit\one> git status
On branch pinkmode
nothing to commit, working tree clean
PS C:\learngit\one> git merge master
Auto-merging pink.txt
CONFLICT (content): Merge conflict in pink.txt
Automatic merge failed; fix conflicts and then commit the result.
PS C:\learngit\one> git merge master
fatal: You have not concluded your merge (MERGE_HEAD exists).
Please, commit your changes before you merge.
PS C:\learngit\one> git status
On branch pinkmode
All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
        modified:   pink.txt

PS C:\learngit\one> git commit -m "added gautam"
[pinkmode fc28693] added gautam
PS C:\learngit\one> git merge master
Already up to date.
PS C:\learngit\one> git checkout master
Switched to branch 'master'
PS C:\learngit\one> git add pink.txt
PS C:\learngit\one> git commit -m "added abi"
[master 4f65ddf] added abi
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\learngit\one> git checkout pinkmode
Switched to branch 'pinkmode'
PS C:\learngit\one> git add pink.txt
PS C:\learngit\one> git commit -m "added abi"
[pinkmode fd34f85] added abi
 1 file changed, 1 insertion(+)
PS C:\learngit\one> git merge pinkmode
Already up to date.
PS C:\learngit\one> git stash
No local changes to save
PS C:\learngit\one> git stash clear
PS C:\learngit\one> git stash clear
PS C:\learngit\one> git branch --delete pinkmode
error: the branch 'pinkmode' is not fully merged
hint: If you are sure you want to delete it, run 'git branch -D pinkmode'
hint: Disable this message with "git config advice.forceDeleteBranch false"
PS C:\learngit\one> git branch --d pinkmode
error: the branch 'pinkmode' is not fully merged
hint: If you are sure you want to delete it, run 'git branch -D pinkmode'
hint: Disable this message with "git config advice.forceDeleteBranch false"
PS C:\learngit\one> git branch --D pinkmode
error: unknown option `D'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --[no-]verbose    show hash and subject, give twice for upstream branch
    -q, --[no-]quiet      suppress informational messages
    -t, --[no-]track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --[no-]set-upstream-to <upstream>
                          change the upstream info
    --[no-]unset-upstream unset the upstream info
    --[no-]color[=<when>] use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --[no-]abbrev[=<n>]   use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --[no-]delete     delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --[no-]move       move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    --[no-]omit-empty     do not output a newline after empty formatted refs
    -c, --[no-]copy       copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --[no-]list       list branch names
    --[no-]show-current   show current branch name
    --[no-]create-reflog  create the branch's reflog
    --[no-]edit-description
                          edit the description for the branch
    -f, --[no-]force      force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --[no-]column[=<style>]
                          list branches in columns
    --[no-]sort <key>     field name to sort on
    --[no-]points-at <object>
                          print only branches of the object
    -i, --[no-]ignore-case
                          sorting and filtering are case insensitive
    --[no-]recurse-submodules
                          recurse through submodules
    --[no-]format <format>
                          format to use for the output

PS C:\learngit\one> git branch -D pinkmode
Deleted branch pinkmode (was fd34f85).
PS C:\learngit\one> git branch
  bug-fix
* master
  seconf-branch
PS C:\learngit\one> git branch pinkmode
PS C:\learngit\one> git switch pinkmode
D       pink.txt
Switched to branch 'pinkmode'
PS C:\learngit\one> git branch
  bug-fix
  master
* pinkmode
  seconf-branch
PS C:\learngit\one> git status
On branch pinkmode
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pink.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add .
PS C:\learngit\one> git commit -m "pink create"
[pinkmode 5da5c9a] pink create
 1 file changed, 1 insertion(+), 2 deletions(-)
PS C:\learngit\one> git checkout master
Switched to branch 'master'
PS C:\learngit\one> git add .
PS C:\learngit\one> git commit -m "pink edited"
[master 6405375] pink edited
 1 file changed, 3 insertions(+), 2 deletions(-)
PS C:\learngit\one> git checkout pinkmode
Switched to branch 'pinkmode'
PS C:\learngit\one> git checkout master
Switched to branch 'master'
PS C:\learngit\one> git checkout pinkmode
Switched to branch 'pinkmode'
PS C:\learngit\one> git merge master
Auto-merging pink.txt
CONFLICT (content): Merge conflict in pink.txt
Automatic merge failed; fix conflicts and then commit the result.
PS C:\learngit\one> git merge master
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
PS C:\learngit\one> git checkout pinkmode
pink.txt: needs merge
error: you need to resolve your current index first
PS C:\learngit\one> git merge master
fatal: You have not concluded your merge (MERGE_HEAD exists).
Please, commit your changes before you merge.
PS C:\learngit\one> git add .
PS C:\learngit\one> git status
On branch pinkmode
All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
        modified:   pink.txt

PS C:\learngit\one> git commit -m "merge"
[pinkmode d423490] merge
PS C:\learngit\one> git checkout master
Switched to branch 'master'
PS C:\learngit\one> git switch -c purple
Switched to a new branch 'purple'
PS C:\learngit\one> git branch
  bug-fix
  master
  pinkmode
* purple
  seconf-branch
PS C:\learngit\one> git status
On branch purple
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        purple.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\learngit\one> git add .
PS C:\learngit\one> git commit -m "purple mode added"
[purple 17c7da7] purple mode added
 1 file changed, 1 insertion(+)
 create mode 100644 purple.txt
PS C:\learngit\one> git checkout master
Switched to branch 'master'
PS C:\learngit\one> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file2.txt

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\learngit\one> git add .
PS C:\learngit\one> git commit -m "purple mode fised"
[master 805e773] purple mode fised
 1 file changed, 3 insertions(+), 1 deletion(-)
PS C:\learngit\one> git branch
  bug-fix
* master
  pinkmode
  purple
  seconf-branch
PS C:\learngit\one> git switch purplemode
fatal: invalid reference: purplemode
PS C:\learngit\one> git rebase master
Current branch master is up to date.
PS C:\learngit\one> git log --oneline
805e773 (HEAD -> master) purple mode fised
6405375 pink edited
4f65ddf added abi
a9bb708 added gautam
441f8f5 checked pink mode
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) conflict resolved
2e53998 added passion
9e87183 added sur-name
6d51f18 added hobby
689bfc0 added name
996320a changed file
86fd17c added two filea
0c46443 changed some changes
655e175 changed username and email
13aafcb updated the file2.txt
1038aa4 commited the files of one folder in the repo
PS C:\learngit\one> git switch purple
Switched to branch 'purple'
PS C:\learngit\one> git rebase master
Successfully rebased and updated refs/heads/purple.
PS C:\learngit\one> git log --oneline
f2ca31e (HEAD -> purple) purple mode added
805e773 (master) purple mode fised
6405375 pink edited
4f65ddf added abi
a9bb708 added gautam
441f8f5 checked pink mode
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) conflict resolved
2e53998 added passion
9e87183 added sur-name
6d51f18 added hobby
689bfc0 added name
996320a changed file
86fd17c added two filea
0c46443 changed some changes
655e175 changed username and email
13aafcb updated the file2.txt
1038aa4 commited the files of one folder in the repo
PS C:\learngit\one> git reflog
f2ca31e (HEAD -> purple) HEAD@{0}: rebase (finish): returning to refs/heads/purple
f2ca31e (HEAD -> purple) HEAD@{1}: rebase (pick): purple mode added
f2ca31e (HEAD -> purple) HEAD@{0}: rebase (finish): returning to refs/heads/purple
f2ca31e (HEAD -> purple) HEAD@{1}: rebase (pick): purple mode added
805e773 (master) HEAD@{2}: rebase (start): checkout master
17c7da7 HEAD@{3}: checkout: moving from master to purple
805e773 (master) HEAD@{4}: commit: purple mode fised
6405375 HEAD@{5}: checkout: moving from purple to master
17c7da7 HEAD@{6}: commit: purple mode added
6405375 HEAD@{7}: checkout: moving from master to purple
6405375 HEAD@{8}: checkout: moving from pinkmode to master
d423490 (pinkmode) HEAD@{9}: commit (merge): merge
5da5c9a HEAD@{10}: checkout: moving from master to pinkmode
6405375 HEAD@{11}: checkout: moving from pinkmode to master
5da5c9a HEAD@{12}: checkout: moving from master to pinkmode
6405375 HEAD@{13}: commit: pink edited
4f65ddf HEAD@{14}: checkout: moving from pinkmode to master
5da5c9a HEAD@{15}: commit: pink create
4f65ddf HEAD@{16}: checkout: moving from master to pinkmode
4f65ddf HEAD@{17}: checkout: moving from pinkmode to master
fd34f85 HEAD@{18}: checkout: moving from master to pinkmode
4f65ddf HEAD@{19}: checkout: moving from pinkmode to master
fd34f85 HEAD@{20}: reset: moving to HEAD
fd34f85 HEAD@{21}: commit: added abi
fc28693 HEAD@{22}: checkout: moving from master to pinkmode
4f65ddf HEAD@{23}: commit: added abi
a9bb708 HEAD@{24}: checkout: moving from pinkmode to master
fc28693 HEAD@{25}: commit (merge): added gautam
6cb91ef HEAD@{26}: checkout: moving from master to pinkmode
a9bb708 HEAD@{27}: commit: added gautam
441f8f5 HEAD@{28}: checkout: moving from pinkmode to master
6cb91ef HEAD@{29}: commit: added abhii
c574e27 HEAD@{30}: commit (merge): added
767f8e9 HEAD@{31}: checkout: moving from master to pinkmode
441f8f5 HEAD@{32}: commit: checked pink mode
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) HEAD@{33}: checkout: moving from pinkmode to master
767f8e9 HEAD@{34}: checkout: moving from seconf-branch to pinkmode
e3ed1e1 (seconf-branch) HEAD@{35}: checkout: moving from bug-fix to seconf-branch
9cf2e0c (bug-fix) HEAD@{36}: checkout: moving from master to bug-fix
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) HEAD@{37}: checkout: moving from pinkmode to master
767f8e9 HEAD@{38}: commit: add pink mode
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) HEAD@{39}: checkout: moving from master to pinkmode
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) HEAD@{40}: reset: moving to HEAD
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) HEAD@{41}: reset: moving to HEAD
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) HEAD@{42}: checkout: moving from seconf-branch to master
e3ed1e1 (seconf-branch) HEAD@{43}: checkout: moving from bug-fix to seconf-branch
9cf2e0c (bug-fix) HEAD@{44}: checkout: moving from master to bug-fix
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) HEAD@{45}: reset: moving to HEAD
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) HEAD@{46}: reset: moving to HEAD
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) HEAD@{47}: checkout: moving from bug-fix to master
9cf2e0c (bug-fix) HEAD@{48}: commit: abhi
2b5768c HEAD@{49}: reset: moving to HEAD
!q
sh: line 1: q: command not found
!done  (press RETURN)
PS C:\learngit\one> git reflog --hard 767f8e9
fatal: unrecognized argument: --hard
PS C:\learngit\one> git reset --hard 767f8e9
HEAD is now at 767f8e9 add pink mode
PS C:\learngit\one> git log --oneline
767f8e9 (HEAD -> purple) add pink mode
d49dd88 (tag: abhi2, tag: abhi1, tag: abhi) conflict resolved
2e53998 added passion
9e87183 added sur-name
6d51f18 added hobby
689bfc0 added name
996320a changed file
86fd17c added two filea
0c46443 changed some changes
655e175 changed username and email
13aafcb updated the file2.txt
1038aa4 commited the files of one folder in the repo
PS C:\learngit\one> git reset --hard f2ca31e
HEAD is now at f2ca31e purple mode added
PS C:\learngit\one> git merge
fatal: No remote for the current branch.
PS C:\learngit\one> git branch
  bug-fix
  master
  pinkmode
* purple
  seconf-branch
PS C:\learngit\one>


PS C:\learngit\one> git branch  
  bug-fix
  master
  pinkmode
* purple
  seconf-branch
PS C:\learngit\one> git switch master
Switched to branch 'master'
PS C:\learngit\one> git branch -m main 
PS C:\learngit\one> git branch    
  bug-fix
* main
  pinkmode
  purple
  seconf-branch
PS C:\learngit\one> git remote add origin https://github.com/abhigtm-cloud/learngit.git
PS C:\learngit\one> git push origin main                            
Enumerating objects: 51, done.
Counting objects: 100% (51/51), done.
Delta compression using up to 4 threads
Compressing objects: 100% (37/37), done.
Writing objects: 100% (51/51), 4.04 KiB | 114.00 KiB/s, done.       
Total 51 (delta 12), reused 0 (delta 0), pack-reused 0 (from 0)     
remote: Resolving deltas:   0% (0/remote: Resolving deltas:   8% (1/remote: Resolving deltas:  16% (2/remote: Resolving deltas:  25% (3/remote: Resolving deltas:  33% (4/remote: Resolving deltas:  41% (5/remote: Resolving deltas:  50% (6/remote: Resolving deltas:  58% (7/remote: Resolving deltas:  66% (8/remote: Resolving deltas:  75% (9/remote: Resolving deltas:  83% (10remote: Resolving deltas:  91% (11remote: Resolving deltas: 100% (12remote: Resolving deltas: 100% (12/12), done.
To https://github.com/abhigtm-cloud/learngit.git
 * [new branch]      main -> main 
PS C:\learngit\one> git status    
On branch main                    
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)        
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt     

no changes added to commit (use "git add" and/or "git commit -a")   
PS C:\learngit\one> git add . 
PS C:\learngit\one> git commit -m "add hola migo"
[main 2550da7] add hola migo
 1 file changed, 1 insertion(+)   
PS C:\learngit\one> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 283 bytes | 94.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)       
remote: Resolving deltas:   0% (0/remote: Resolving deltas:  50% (1/remote: Resolving deltas: 100% (2/remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/abhigtm-cloud/learngit.git
   805e773..2550da7  main -> main 
PS C:\learngit\one> git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
PS C:\learngit\one> git status    
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:    
  (use "git add <file>..." to update what will be committed)        
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file1.txt     

no changes added to commit (use "git add" and/or "git commit -a")   
PS C:\learngit\one> git add .     
PS C:\learngit\one> git commit -m "add hola migo"
[main 51ab982] add hola migo
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\learngit\one> git push      
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 278 bytes | 92.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)       
remote: Resolving deltas:   0% (0/remote: Resolving deltas:  50% (1/remote: Resolving deltas: 100% (2/remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/abhigtm-cloud/learngit.git
   2550da7..51ab982  main -> main 
PS C:\learngit\one> 