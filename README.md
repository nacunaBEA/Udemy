# Udemy
Udemy exersices
Windows PowerShell
Copyright (C) Microsoft Corporation. Todos los derechos reservados.

Prueba la nueva tecnología PowerShell multiplataforma https://aka.ms/pscore6

PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git version
git version 2.24.0.windows.2
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git init
Initialized empty Git repository in C:/Users/nacuna.IDEAR/Desktop/Archivos Cafe/blogcafe/.git/
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git add .
warning: LF will be replaced by CRLF in index.html.
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git commit -m "primera parte del bog de café"
[master (root-commit) 5bafa12] primera parte del bog de café
 13 files changed, 494 insertions(+)
 create mode 100644 .DS_Store
 create mode 100644 css/normalize.css
 create mode 100644 img/blog1.jpg
 create mode 100644 img/blog3.jpg
 create mode 100644 img/contacto.jpg
 create mode 100644 img/curso1.jpg
 create mode 100644 img/curso2.jpg
 create mode 100644 img/curso3.jpg
 create mode 100644 index.html
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git log
commit 5bafa12c9aa6b440536a6095fd4d29fdf17b96a2 (HEAD -> master)
Author: noe.acuna@sistemabea.mx <57777498+nacunaBEA@users.noreply.github.com>
Date:   Fri Jan 31 17:26:51 2020 -0600
    primera parte del bog de café
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git status -s
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git status -s -b
## master
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git push origin master

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git push master master
fatal: 'master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git push Udemy master 
fatal: 'Udemy' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git remote add origin https://github.com/nacunaBEA/Udemy.git
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe> git push -u origin master
Enumerating objects: 17, done.
Counting objects: 100% (17/17), done.
Delta compression using up to 8 threads
Compressing objects: 100% (17/17), done.
Writing objects: 100% (17/17), 1.59 MiB | 2.79 MiB/s, done.
Total 17 (delta 0), reused 0 (delta 0)
To https://github.com/nacunaBEA/Udemy.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
PS C:\Users\nacuna.IDEAR\Desktop\Archivos Cafe\blogcafe>   
