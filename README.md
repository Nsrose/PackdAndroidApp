PackdAndroidApp
===============
Android app for the Packd app.

Setup
=====
1. We've decided to use Android Studio as our development software.  
https://developer.android.com/sdk/installing/studio.html  

Make sure you have that downloaded. It should create a workspace in  
the root of your system, called /Androidstudioprojects. This is where  
Android studio will modify and run your projects.  

2. Navigate in to your /Androidstudioprojects folder, using the terminal.  
3. Clone this repo with the following command:  
git clone https://github.com/Nsrose/PackdAndroidApp.git  
4. Make a branch with your name so you can work on it and not interfere with the master branch:  
git branch mybranchname  
git checkout mybranchname  
git push origin mybranchname  

5. Now you're set up to work on the project on your branch whenever you wish!


Git Notes
=========

Git is super important. It’s what we’ll be using to manage versions and make sure one person doesn’t accidentally destroy the whole project. That said, there are guidelines we’ll need to follow.

Workflow:
---------
1. cd into your PackdAndroidApp folder (IN YOUR ANDROIDSTUDIOPROJECTS FOLDER)
2. Pull the changes from master into your master branch
3. Branch off into whatever branch you’re currently working on
4. Do some work/editing
5. Add /Commit/ Push your changes to your branch
6. Submit a pull request to merge your branch with master

Actual Code Example (I'm working on a branch called ButtonFix):
---------------------------------------------------------------
$ cd PackdAndroidApp  
$ git branch #making sure I'm on the master  
$ git checkout master #puts me on the master branch  
$ git pull origin master  
$ git checkout ButtonFix  
Do work/ editing here  
$ git add .  
$ git commit -m "fixed the button"  
$ git push origin ButtonFix  
Submit a pull request: https://help.github.com/articles/creating-a-pull-request


