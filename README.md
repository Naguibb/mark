# About Git
is a DevOps tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development. Linus Torvalds created Git in 2005 for the development of the Linux kernel.

## Create our first repo on git

steps :

---
git init

git add .

git commit -m "Push existing project to GitLab"


git push -u source(origin) master

---
### Clone repo

Cloning a repository gives you a copy of its content, including commits and branches. Your local Git client downloads the remote repository, then checks out its main branch into a new directory on your machine.

Git support many cloning protocols:


ssh protocol :

---

git clone ssh://user@server:project.git

---


http protocol :

---

git clone http://server:project.git

---


git protocol :

---

git clone myprojects/project

---


file protocol :

---

git clone  fileaddress

---


Manually from interface:

---
git clone URL. 

Go to the project’s overview page.

Select Clone.

Under Open in your IDE, select Visual Studio Code (SSH) or Visual Studio Code (HTTPS).

Select a folder to clone the project into.

After Visual Studio Code clones your project, it opens the folder.

---


#### Some usefull command

To know status :

---

git status

---

To push any number of files :

---

git generaterandomfiles (num of files) name.exetion

---

To remove file :

---

git rm filename

---
