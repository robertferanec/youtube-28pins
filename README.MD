## 28Pins Project

### Starting
To download this project to your computer:
1. Install GIT: https://git-scm.com/downloads
1. Go into your main project directory, open commad line and run:<br />
`git clone https://github.com/your_username/your_project.git`

## Using Git in Altium
1. **Save:** Once you make any changes, save the file or project
1. **Commit:** Right click on the file or project, then Version Control -> Commit. Add a note what changes you have done. This not will be still local until you do not push the changes. See the next step.
1. **Push:** When you would like to upload all the changes to github, right click on the file / project -> Version Control -> Push
1. **Check:** Go to your github to see if everything was uploaded correctly

## Using Git from command line (Manually)
1. **Open cmd:** Once you make some updates, go into your project directory, open commad line and run:<br />
1. `git status` #this will show you what changes you have done<br />
1. `git add [path/file]` #this will prepare that specific file for commit, to add all files at once, use add . <br />
1. `git commit -m "Change description"` #this will commit the changes with specific description<br />
1. `git push origin master` # this will copy your changes to Github<br />

### Download the latest changes
If you would like to download the latest files from Github, then:<br />
1. `git pull origin master` # this will download the latest files from Github to your local computer<br />
