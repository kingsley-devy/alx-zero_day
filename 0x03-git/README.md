# Repo-Session : Understanding Git Basic Commands and Git Workflow

## Task 1:
* Create a new directory called 0x03-git in you alx-zero_day repo.
* Make sure you include a not empty README.md in your directory at the root of your repo alx-zero_day and in the directory 0x03-git._

## Task 2:
_For the moment we have an empty project directory containing only a README.md. It’s time to code!_

* Create these directories at the root of your project: bash, c, js
* Create these empty files:
* c/c_is_fun.c
* js/main.js
* js/index.js
* Create a file bash/alx with these two lines inside: #!/bin/bash and echo "ALX"
* Create a file bash/school with these two lines inside: #!/bin/bash and echo "School"
* Add all these new files to git
* Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

## Task 3:
__A branch is like a copy of your project. It’s used mainly for:__

* adding a feature in development
* collaborating on the same project with other developers
* not breaking your entire repository
* not upsetting your co-workers
* The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.

* For this project, create a branch update_script and in this branch:

* Create an empty file named bash/98
* Update bash/alx by replacing echo "ALX" with echo "ALX School"
* Update bash/school by replacing echo "School" with echo "The school is open!"
* Add and commit these changes (message: “My personal work”)
* Push this new branch Tips

_Perfect! You did an amazing update in your project and it’s isolated correctly from the main branch._

_Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:_

* Change branch to main
* Update the file bash/alx by replacing echo "ALX" with echo "ALX School is so cool!"
* Delete the directory js
* Commit your changes (message: “Hot fix”) and push to the origin

## Task 4
_Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes._

_For this task – and only for this task – please update your file README.md in the main branch from GitHub.com. It’s the only time you are allowed to update and commit from GitHub interface._

_After you have done that, in your terminal:_

* Get all changes of the main branch locally (i.e. your README.md file will be updated)
* Create a new file up_to_date at the root of your directory and in it, write the git command line used
* Add up_to_date to git, commit (message: “How to be up to date in git”), and push to the origin

__ALX SE__.






