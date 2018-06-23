# 0. Create and setup your Git and Github account
Git is installed on your iMac provided by Holberton, but if you’re using another computer, you might have to install it yourself.

As a Holberton School student, you are eligible to get a GitHub student developer pack, with some nice goodies. Get you pack here: https://education.github.com/pack
Configure the basics you need on your local account that will be part of your commits: your name, your email. Tips
In Github.com:

Create your first repository (please use the graphical interface)
name: my_first_repository
description: I'm now a Holberton Student, it's my first repository as a full-stack engineer
public
no Readme, .gitignore or license
In your computer, open a terminal to:

navigate to your home/login directory. Tips
create a directory my_first_repository. Tips
navigate to this new directory. Tips
initialize git and add the remote origin
create a file README.md with Emacs (or other command line editors) and write a small Markdown text to present this project. This file is mandatory in all Holberton School projects
add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (you will probably need to set your login/password to push to the remote server)
Good job!

You did your push in your first repository of your first task of your first Holberton School project.
# 1. Coding fury road
For the moment we have an empty project, only the description with the README.md, it’s time to code!

create these directories at the root of your project: bash, c, js
create empty files:
c/c_is_fun.c
js/main.js
js/index.js
create a file bash/holberton with these two lines inside: #!/bin/bash and echo "Holberton"
create a file bash/school with these two lines inside: #!/bin/bash and echo "School"
add all these new files to git
commit your changes (message: “Starting to code today, so cool”) and push to the remote server
# 2. Collaboration is the base of a company
A branch is like a copy of your project. It’s used mainly for:

to not breaking your repository
to add a feature in development
collaboration on the same project with someone else
to not upset your co-worker
The goal of a branch is to isolate your work with the main code of your project or with coworker’s work.

For your first project, you will create a branch update_script and in this branch you will:

create an empty file bash/98
update bash/holberton by replacing echo "Holberton" by echo "Holberton School"
update bash/school by replacing echo "School" by echo "The school is open!"
add and commit these changes (message: “My personal work”)
push this new branch. Tips
Perfect! you did an amazing update in your project and it’s isolated correctly from the master branch.

Ho wait, your manager needs a quick fix in your project and it should be deployed now:

change branch to master
update the file bash/holberton by replacing echo "Holberton" by echo "Holberton School is so cool!"
delete the directory js
commit your changes (message: “Hot fix”) and push to the origin
Ouf, hot fix is done!
# 3. Collaboration: be up to date
Of course, you can also work on the same branch as your co-workers and it’s better for you to be up to date with their changes.

For this task, and only for this task, please update your file README.md in the master branch from Github.com. It’s the only time you are allowed to update and commit from Github interface.

When it’s done, in your terminal:

get locally all changes of the master branch (your README.md file will be updated)
write in a file up_to_date (at the root of your repository) the git command line used
add this new file up_to_date, commit (message: “How to be up to date in git”) and push to the origin