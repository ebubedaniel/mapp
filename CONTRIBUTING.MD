﻿# HOW TO WORK ON THE PROJECT'S FILES
## Using Github for your first time working in the project:
* Sign in or sign up if you don't currently have a Github account.
* Use the 'fork' button on the project's page to create your own copy of the repository
* Google and install the Git application on your computer and open 'Git Bash'
* Enter 'git config --global user.email "you@example.com"' and 'git config --global user.name "Your Name"'
* Click 'Clone' on the project's webpage and copy the link that appears
* Go back to Git Bash and enter 'git clone <paste the link here>' without the angle brackets
* Enter 'cd mapp' to change youor current directory

## To add new files to the repository
* Enter 'git status' New files are shown in red
* Enter 'git add <file name>' or 'git add .' to add all uncommitted files
* Enter 'git status' again to show files ready to be committed
* Enter 'git commit -m "Commit Message"'Commit message highlights whatever changes you have made in terms of action performed eg. "Edit Author List" instead of "I edited author list"
* Enter 'git push origin master' to push the changes to the master repository; supply your git username and password in the provided dialiog box if requested.
* Click on New pull request, selct dev to merge to the dev branch

## Picking a task to work on
* Go to the projects [Pivotal Tracker page](https://www.pivotaltracker.com/n/projects/2078365)
* Pick a task to work on and click on start
* Work on the task and commit the new files to github
* Click Deliver and put a link to the github pull request under the comments section
* Click finish, so your work can be reviewed and accepted.
