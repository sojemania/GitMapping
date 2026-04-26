olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject

**$ git config --global user.email "olasojirawlings@gmail.com"**



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject

**$ git config --global user.name "sojemania"**



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject

**$ git config --global user.email**

olasojirawlings@gmail.com



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject

**$ git config --global user.name**

sojemania



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject

**$ git init**

Initialized empty Git repository in C:/Users/olaso/OneDrive/Documents/GitProject/.git/



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git status**

On branch master



No commits yet



Untracked files:

&#x20; (use "git add <file>..." to include in what will be committed)

&#x20;       Testing\_git\_connect.txt



nothing added to commit but untracked files present (use "git add" to track)



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git add \*.txt**



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git status**

On branch master



No commits yet



Changes to be committed:

&#x20; (use "git rm --cached <file>..." to unstage)

&#x20;       new file:   Testing\_git\_connect.txt





olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ Git commit -m "Addeded new TXT file"**

\[master (root-commit) 5ed49a9] Addeded new TXT file

&#x20;1 file changed, 0 insertions(+), 0 deletions(-)

&#x20;create mode 100644 Testing\_git\_connect.txt



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git status**

On branch master

nothing to commit, working tree clean



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ Git remote add origin https://github.com/sojemania/GitMapping.git**



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git remote show origin**

\* remote origin

&#x20; Fetch URL: https://github.com/sojemania/GitMapping.git

&#x20; Push  URL: https://github.com/sojemania/GitMapping.git

&#x20; HEAD branch: (unknown)



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git push -u origin master**

info: please complete authentication in your browser...

Enumerating objects: 3, done.

Counting objects: 100% (3/3), done.

Delta compression using up to 12 threads

Compressing objects: 100% (2/2), done.

Writing objects: 100% (3/3), 236 bytes | 236.00 KiB/s, done.

Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

To https://github.com/sojemania/GitMapping.git

&#x20;\* \[new branch]      master -> master

branch 'master' set up to track 'origin/master'.





olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git log**

commit 5ed49a9bfdfa25a32084f3cd4f537263e0d7eddd (HEAD -> master, origin/master)

Author: sojemania <olasojirawlings@gmail.com>

Date:   Sun Apr 26 12:11:38 2026 -0400



&#x20;   Addeded new TXT file



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git help**

usage: git \[-v | --version] \[-h | --help] \[-C <path>] \[-c <name>=<value>]

&#x20;          \[--exec-path\[=<path>]] \[--html-path] \[--man-path] \[--info-path]

&#x20;          \[-p | --paginate | -P | --no-pager] \[--no-replace-objects] \[--no-lazy-fetch]

&#x20;          \[--no-optional-locks] \[--no-advice] \[--bare] \[--git-dir=<path>]

&#x20;          \[--work-tree=<path>] \[--namespace=<name>] \[--config-env=<name>=<envvar>]

&#x20;          <command> \[<args>]



These are common Git commands used in various situations:



start a working area (see also: git help tutorial)

&#x20;  clone      Clone a repository into a new directory

&#x20;  init       Create an empty Git repository or reinitialize an existing one



work on the current change (see also: git help everyday)

&#x20;  add        Add file contents to the index

&#x20;  mv         Move or rename a file, a directory, or a symlink

&#x20;  restore    Restore working tree files

&#x20;  rm         Remove files from the working tree and from the index



examine the history and state (see also: git help revisions)

&#x20;  bisect     Use binary search to find the commit that introduced a bug

&#x20;  diff       Show changes between commits, commit and working tree, etc

&#x20;  grep       Print lines matching a pattern

&#x20;  log        Show commit logs

&#x20;  show       Show various types of objects

&#x20;  status     Show the working tree status



grow, mark and tweak your common history

&#x20;  backfill   Download missing objects in a partial clone

&#x20;  branch     List, create, or delete branches

&#x20;  commit     Record changes to the repository

&#x20;  history    EXPERIMENTAL: Rewrite history

&#x20;  merge      Join two or more development histories together

&#x20;  rebase     Reapply commits on top of another base tip

&#x20;  reset      Set `HEAD` or the index to a known state

&#x20;  switch     Switch branches

&#x20;  tag        Create, list, delete or verify tags



collaborate (see also: git help workflows)

&#x20;  fetch      Download objects and refs from another repository

&#x20;  pull       Fetch from and integrate with another repository or a local branch

&#x20;  push       Update remote refs along with associated objects



'git help -a' and 'git help -g' list available subcommands and some

concept guides. See 'git help <command>' or 'git help <concept>'

to read about a specific subcommand or concept.

See 'git help git' for an overview of the system.



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git branch Dependant**



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git branch**

&#x20; Dependant

\* master



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git checkout Dependant**

Switched to branch 'Dependant'



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (Dependant)

**$ git status**

On branch Dependant

Untracked files:

&#x20; (use "git add <file>..." to include in what will be committed)

&#x20;       Testing\_git\_connect2.txt



nothing added to commit but untracked files present (use "git add" to track)





olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (Dependant)

**$ Git add Testing\_git\_connect2.txt**



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (Dependant)

**$ git status**

On branch Dependant

Changes to be committed:

&#x20; (use "git restore --staged <file>..." to unstage)

&#x20;       new file:   Testing\_git\_connect2.txt





olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (Dependant)

**$ Git commit -m "Added file to dependant branch"**

\[Dependant a2adfc8] Added file to dependant branch

&#x20;1 file changed, 0 insertions(+), 0 deletions(-)

&#x20;create mode 100644 Testing\_git\_connect2.txt



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (Dependant)

**$ git status**

On branch Dependant

nothing to commit, working tree clean



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (Dependant)

**$ git push -u origin Dependant**

Enumerating objects: 3, done.

Counting objects: 100% (3/3), done.

Delta compression using up to 12 threads

Compressing objects: 100% (2/2), done.

Writing objects: 100% (2/2), 270 bytes | 270.00 KiB/s, done.

Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

remote:

remote: Create a pull request for 'Dependant' on GitHub by visiting:

remote:      https://github.com/sojemania/GitMapping/pull/new/Dependant

remote:

To https://github.com/sojemania/GitMapping.git

&#x20;\* \[new branch]      Dependant -> Dependant

branch 'Dependant' set up to track 'origin/Dependant'.



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (Dependant)

**$ git checkout master**

Switched to branch 'master'

Your branch is up to date with 'origin/master'.



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git merge Dependant**

Updating 5ed49a9..a2adfc8

Fast-forward

&#x20;Testing\_git\_connect2.txt | 0

&#x20;1 file changed, 0 insertions(+), 0 deletions(-)

&#x20;create mode 100644 Testing\_git\_connect2.txt



olaso@OlasojiOba MINGW64 \~/OneDrive/Documents/GitProject (master)

**$ git push -u origin master**

Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

To https://github.com/sojemania/GitMapping.git

&#x20;  5ed49a9..a2adfc8  master -> master

branch 'master' set up to track 'origin/master'.





