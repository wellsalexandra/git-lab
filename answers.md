1. git version 2.17.1
2. user.name=Alexandra Wells
   user.email=aw771620@ohio.edu
3. These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

4. On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

5. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        answers.md

6. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md
        new file:   answers.md

7. On branch master
nothing to commit, working tree clean

8. On branch master
nothing to commit, working tree clean
jestell@odd15:~/CS2400x/CS2400studentWells/lab2/git-lab$ git log
commit c28d197b443087ffba1168f2d7b832345010171f (HEAD -> master)
Author: Alexandra Wells <aw771620@ohio.edu>
Date:   Tue Jan 18 18:47:34 2022 -0500

    Initial commit

9. Counting objects: 4, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 282 bytes | 141.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/wellsalexandra/git-lab.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

10. No
11. To https://github.com/wellsalexandra/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/wellsalexandra/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
jestell@odd15:~/CS2400x/CS2400studentWells/lab2/git-lab$ git push
Username for 'https://github.com': wellsalexandra
Password for 'https://wellsalexandra@github.com':
To https://github.com/wellsalexandra/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/wellsalexandra/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
jestell@odd15:~/CS2400x/CS2400studentWells/lab2/git-lab$

12. Yes they were!
13. .  ..  .git  .gitignore  README.md
