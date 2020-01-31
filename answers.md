#Answer1:
git version 2.17.1

#Answer2:
user.name=Cameron Spaulding
user.email=cs237217@ohio.edu

#Answers3:
cspauldi@sp-017:~$ git --help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

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

#//*************************************************************************************************
// 
//The bottom answers 4 ,5 ,and 6 were all commited before I could record the answers. I was       uncertain how to un-commit them so here is what I has from the log-status function
//
#//*************************************************************************************************


#Answer4:
README.md
answers.md
md

#Answer5:
answers.md
md

#Answer6:
md

#Answer7:
md

nothing to commit, working tree clean

#Answer8:
commit 26c62f72a81cc7ccb0685462cad283537df0b584 (HEAD -> master)
Author: Cameron Spaulding <cs237217@ohio.edu>
Date:   Thu Jan 30 19:48:48 2020 -0500

    Here we go...

commit e7e935c69be6393df42f568e4e1cd7e6f317eac7
Author: Cameron Spaulding <cs237217@ohio.edu>
Date:   Thu Jan 30 19:44:11 2020 -0500

    I hope the extra md is supposed to be there...


#// I deleted the md file due to belief it was an error. 


#Answer9:
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

#Answer10:
No, the changes commited online where not represented in the local terminal.

#Answer11:
o https://github.com/cs237217/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/cs237217/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

The terminal rejected my push.

#Answer12: 
Yes! Finally the git pull function represented the changes made in GitHub in my terminal.

#Answer13:
.  ..  .git  .gitignore  README.md

