 # Answer1 
 git version 2.31.1

 # Answer2 : 
 credential.helper=osxkeychain
user.name=kn478619
user.email=kn478619@ohio.edu

# Answer3 :
 usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

# Answer4: 
 On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md
nothing added to commit but untracked files present (use "git add" to track)

# Answer5 :
 On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
yes, I noticed the change in colour.

# Answer6:
 On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

# Answer7:
 [master (root-commit) 6d13602] Initial commit
 2 files changed, 79 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md

 Answer8: commit 6d13602f752fd9790fedb3d3ce196c1b843a9c34 (HEAD -> master)
Author: kn478619 <kn478619@ohio.edu>
Date:   Mon May 10 23:25:50 2021 -0400

    Initial commit

# Answer9: 
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

# Answer10: 
No changes were not seen made in online.
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

# nswer11:  
! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/kn478619/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

# Answer12: Yes, changes made online were seen.
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 703 bytes | 175.00 KiB/s, done.
From https://github.com/kn478619/git-lab
   b8855eb..f65b52b  main       -> origin/main
Updating b8855eb..f65b52b
Fast-forward
 README.md | 7 ++++++-
 1 file changed, 6 insertions(+), 1 deletion(-)

 # Answer13:
 .               ..              .git            .gitignore      README.md







