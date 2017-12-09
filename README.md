
## PRE INSTALLATION INSTRUCTIONS ##
#### ONLY FOLLOW PRE INSTALLATION IF GIT AND NODE.JS ARE NOT ALREADY INSTALLED ####

1. Download and install git at:  
		**https://git-scm.com/downloads**

2. Download and install node.js at:  
		**https://nodejs.org/en/download/**

3. Open GitBash (Windows), or Terminal (MacOSX)

4. Type the following and press enter:  
		**npm install gulp-cli --global**




## MAIN INSTALLATION INSTRUCTIONS ##
#### START HERE IF GIT AND NODE.JS ARE ALREADY INSTALLEED ####

1. Navigate to working folder for your projects.  
		(in commandline GitBash or Terminal - eg. **cd Desktop/GSites**) 

2. Type the following and press enter:  
		**git clone git@gitlab.com:Fetzu/seed-project.git**

3. After download is complete, navigate into the new seed-project folder.  
		(in commandline GitBash or Terminal - eg. **cd seed-project**) 

4. Type the following and press enter:  
		**npm install**

5. Have a cup of coffee, this will take some time to complete the download.  

6. Type the following and press enter:  
		**gulp watch**




## EXTRA STEPS - RENAMING THE PROJECT FOLDER "seed-project" ##
If you rename the project folder from "seed-project" to something else, make sure you open the 'package.json' file and change line 2 from:  
		**"name": "seed-project",**  
to:  
		**"name": "your-new-folder-name",**  




## HOW TO USE ##

This template project has some automation to help with learning web development. To activate this automation you **MUST** type the following, in a commandline, and press enter:  
		**gulp watch**

#### 1. DISPLAY CHANGES AFTER SAVING CSS AND HTML FILES ####  
		The browsers that are displaying the website will be automatically **REFRESHED** when an **HTML** file is saved, and all changes in **CSS** files will be automatically **INJECTED** when a **CSS** file is saved.  

#### 2. WEBSITE IS SYNCED ACROSS ALL BROWSERS ####  
		All browsers are synced when you have the website opened in multiple browsers. Scrolling in one, scrolls in the others automatically. Opening a menu in one, opens a menu in the others automatically. You can also view the website across devices by finding the output (shown below) in the commandline after using **gulp watch**, and putting the **External** URL in the new devices browser. NOTE: The device MUST be connected to the same network as the computer that has the local files.

		**[Browsersync] Access URLs:
 --------------------------------------
       Local: http://localhost:3000
    **External: http://192.168.1.100:3000**
 --------------------------------------
          UI: http://localhost:3001
 UI External: http://192.168.1.100:3001
 --------------------------------------**








