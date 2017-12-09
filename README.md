
PRE INSTALLATION INSTRUCTIONS
### ONLY FOLLOW PRE INSTALLATION IF THE FOLLOWING ARE NOT ALREADY INSTALLED ###

1. Download and install git at:
		https://git-scm.com/downloads

2. Download and install node.js at:
		https://nodejs.org/en/download/

3. Open GitBash (Windows), or Terminal (MacOSX)

4. Type the following and press enter:
		npm install gulp-cli --global




MAIN INSTALLATION INSTRUCTIONS
### START HERE IF GIT AND NODE.JS ARE ALREADY INSTALLEED ###

1. Navigate to working folder for your projects.
		(in commandline GitBash or Terminal - eg. cd Desktop/GSites) 

2. Type the following and press enter:
		git clone git@gitlab.com:Fetzu/seed-project.git

3. After download is complete, navigate into the new seed-project folder.
		(in commandline GitBash or Terminal - eg. cd seed-project) 

4. Type the following and press enter:
		npm install

5. Have a cup of coffee, this will take some time to complete the download.

6. Type the following and press enter:
		gulp watch




EXTRA STEPS - RENAMING THE PROJECT FOLDER "seed-project"
If you rename the project folder from "seed-project" to something else, make sure you open the 'package.json' file and change line 2 from: 
		"name": "seed-project",
to:
		"name": "your-new-folder-name",





