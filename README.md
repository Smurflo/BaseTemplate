# Base Template

***

Kyle's Base template for future projects.

***

## Setup

1. If you're not already set up to run PHP applications locally, you'll want to install that first.  Some good options would be [MAMP](https://www.mamp.info/en/) for OS X, or [WampServer](http://www.wampserver.com/en/) if you're running Windows [Note: download 32 bit version of WAMP even if your windows is 64 bit. The 64 bit version seems to have problems].
2. Clone the repository into your desired folder. For Windows with WAMP, your default root will be C:\wamp\www. For OS X with MAMP, your default root will be something like /Applications/MAMP/htdocs. (See "How to Clone")
3. Go into the root directory of the project and open up settings.php with your favorite text editor, I recommend phpstorm (see below).  You'll want to change the environment to "local" (line 8) and also change the local environment settings to match your username/password/databasename.
4. Start up MAMP/WampServer if you haven't already using the desktop shortcut, open up your browser,and navigate to http://localhost/. If the project is in a subdirectory (e.g BaseTemplate) you will need to navigate to http://localhost/BaseTemplate
5. Aaand you're done, time to start on your real project

***

## Project Overview

Doesn't actually have any functionality 
  * Just a jumbotron page with links to 3 other pages
  * Placeholder login page
  * Navbar
  * Some basic javascript
  * Comes with jquery and bootstrap

***

## How to Clone
1. Download git: https://git-scm.com/downloads default settings are fine (as of 12/13/16)
2. open root directory (eg. C:\wamp\www) [Note: it may be slighlty different for you (e.g C:\wamp64\www)]
3. Right click on white space -> select "Git Bash Here"
4. Enter "git clone https://github.com/Smurflo/BaseTemplate" into the git window

***

### Text Editor
#### phpstorm (requires student account or $$):
1. Download at https://www.jetbrains.com/phpstorm/download/#section=windows-version
2. Create associasions as you wish (I selected all of them)

#### Other Options
   * Sublime Text (for Mac)
   * Eclipse
   * (just Google it)