# LaboratorioCViernes
Practicas FCFM Laboratorio de Programacion Estructurada.

FCFM@Aula211-12 MINGW32 ~
$ cd Documents/

FCFM@Aula211-12 MINGW32 ~/Documents
$ ls
 desktop.ini           'Plantillas personalizadas de Office'/
 LaboratorioCViernes/   TeamViewerPortable/
'Mi música'@           'Virtual Machines'/
'Mis imágenes'@        'Visual Studio 2008'/
'Mis vídeos'@          'Visual Studio 2010'/
 NetBeansProjects/

FCFM@Aula211-12 MINGW32 ~/Documents
$ cd LaboratorioCViernes/

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes
$ git clone https://github.com/ErickLC0808/LaboratorioCViernes.git
fatal: destination path 'LaboratorioCViernes' already exists and is not an empty directory.

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes
$ cd LaboratorioCViernes/

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (master)
$ ls
 main.c   main.o   Makefile.win  'proyacto base.dev'  'proyacto base.exe'*

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (master)
$ git clone https://github.com/ErickLC0808/LaboratorioCViernes.git
Cloning into 'LaboratorioCViernes'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 7 (delta 0), reused 7 (delta 0), pack-reused 0
Unpacking objects: 100% (7/7), done.

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (master)
$ git checkout -b Practica4
Switched to a new branch 'Practica4'

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> Practica4


FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git STATUS
fatal: cannot handle STATUS as a builtin

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ ls
LaboratorioCViernes/

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git add *
warning: adding embedded git repository: LaboratorioCViernes
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> LaboratorioCViernes
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached LaboratorioCViernes
hint:
hint: See "git help submodule" for more information.

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git add proyecto\ base.dev
fatal: pathspec 'proyecto base.dev' did not match any files

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git add proyeco\ base.exe
fatal: pathspec 'proyeco base.exe' did not match any files

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git status
On branch Practica4
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   LaboratorioCViernes

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Makefile.win
        deleted:    main.c
        deleted:    main.o
        deleted:    proyacto base.dev
        deleted:    proyacto base.exe


FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git commit -m "cambio de proyecto"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'FCFM@Aula211-12.(none)')

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git config --global user.name "erickloracam0808@gmail.com"

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git config --global user.email "erickloracam0808@gmail.com"

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git config --global user.name "ErickLC0808"

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git commit -m "cambio de proyecto"
[Practica4 5a5dc47] cambio de proyecto
 1 file changed, 1 insertion(+)
 create mode 160000 LaboratorioCViernes

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git push
fatal: The current branch Practica4 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin Practica4


FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git commit -m "guardar"
On branch Practica4
Changes not staged for commit:
        modified:   LaboratorioCViernes (untracked content)
        deleted:    Makefile.win
        deleted:    main.c
        deleted:    main.o
        deleted:    proyacto base.dev
        deleted:    proyacto base.exe

no changes added to commit

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git push
fatal: The current branch Practica4 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin Practica4


FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git commit -m "branch"
On branch Practica4
Changes not staged for commit:
        modified:   LaboratorioCViernes (untracked content)
        deleted:    Makefile.win
        deleted:    main.c
        deleted:    main.o
        deleted:    proyacto base.dev
        deleted:    proyacto base.exe

no changes added to commit

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git push
fatal: The current branch Practica4 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin Practica4


FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git status
On branch Practica4
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   LaboratorioCViernes (untracked content)
        deleted:    Makefile.win
        deleted:    main.c
        deleted:    main.o
        deleted:    proyacto base.dev
        deleted:    proyacto base.exe

no changes added to commit (use "git add" and/or "git commit -a")

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git add *

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ git status
On branch Practica4
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   LaboratorioCViernes (untracked content)
        deleted:    Makefile.win
        deleted:    main.c
        deleted:    main.o
        deleted:    proyacto base.dev
        deleted:    proyacto base.exe

no changes added to commit (use "git add" and/or "git commit -a")

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ ls
LaboratorioCViernes/

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes (Practica4)
$ cd LaboratorioCViernes/

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes/LaboratorioCViernes (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        practica 4.1.cpp
        practica 4.1.o

nothing added to commit but untracked files present (use "git add" to track)

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes/LaboratorioCViernes (master)
$ git add *

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes/LaboratorioCViernes (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   practica 4.1.cpp
        new file:   practica 4.1.o


FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes/LaboratorioCViernes (master)
$ git commint -m "practica 4.1."
git: 'commint' is not a git command. See 'git --help'.

The most similar command is
        commit

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes/LaboratorioCViernes (master)
$ git push
git push

FCFM@Aula211-12 MINGW32 ~/Documents/LaboratorioCViernes/LaboratorioCViernes/LaboratorioCViernes (master)
$ git push
Everything up-to-date
