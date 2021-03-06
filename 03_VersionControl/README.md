# 20.03 — [03] Version Control and Collaboration



# General workflow:

* [github.com](https://github.com/) :: make an account
* download git software (Windows; Macs usually have it already)
* `fork` a repository
* `clone`
* *work*
* `add`
* `commit`
* `push` / `pull`
* send `pull request`


# Some command line commands

* `pwd`
	- shows you where you are on a drive (gives you path)
* `ls` / `dir` [on Windows]
	- shows everything in the your current location/folder
* `cd <name of the folder>`
	- takes you to that folder
* `cd ..` 
	- takes you one level up in the tree structure of your computer

# GitHub: Main Commands

* `git clone <link>`
	- clones/downloads a repository on you machine
* `git status`
	- shows the current status of the repository (new, changed, deleted)
* `git add .`
	- adds all new files and modified files to the repository
* `git commit -m "message"
	- saves all files in their current state into the repository, and created a milestone
* `git push origin master`
	- uploads changes to [github.com](https://github.com/)
	- **NB:** sometimes you may get an error, which in most cases means that you need to `pull` first
* `git pull origin master`
	- downloads changes from [github.com](https://github.com/)
* `git log`
	- shows the history of `commit`s; here you can choose where you want to roll back, in case of troubles

# From the syllabus

## Goals:

Learning about version control systems and how they help in the development of  DH project, which are often a lengthy and complex, and require organic collaboration. 


## Software:

* create github account @ https://github.com/

* Github
	- [Win] install from here: https://git-scm.com/downloads 
	- [Mac] github is already on your machine
	- [Win] also install the desktop interface https://desktop.github.com/)
	- Jekyll, a simple, blog-aware, static site generator
	- see Reference Materials below on how to install


## Class:

* Basic `git` functionality
* Starting a website; basics of `markdown`


## Reference Materials:

* Simpkin, Sarah. 2015. “Getting Started with Markdown.” Programming Historian, November. [https://programminghistorian.org/](https://programminghistorian.org/lessons/getting-started-with-markdown).
* Visconti, Amanda. 2016. “Building a Static Website with Jekyll and GitHub Pages.” Programming Historian, April. [https://programminghistorian.org/](https://programminghistorian.org/lessons/building-static-sites-with-jekyll-github-pages).


## Homework:

* Build your website on github from the template at [https://github.com/univie-tnt-2018-summer](https://github.com/univie-tnt-2018-summer/univie-tnt-2018-summer.github.io)
	* `fork`
	* create a repository under your account with the name: `username.github.io`, where username is your github username; the repository with such names are automatically treated by github as a website.
	* copy all files from the forked repository into your new one (`clone` > `copy/paste`)
	* README.md has all the instructions on how to make modifications to your site; play with those!
	* you can pick a different theme for you site (just google `jekyll themes` for options)
* Complete Codecademy’s *Learn Git* [https://www.codecademy.com/learn/learn-git](https://www.codecademy.com/learn/learn-git);
	- if you’d like more practice, there is another one: [https://try.github.io](https://try.github.io) 
* Publish your confirmation screenshot as a post on your new site;
* Also, add a page with this confirmation to the shared (forked site) and send me `pull request`

