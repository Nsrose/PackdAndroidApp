PackdAndroidApp
===============
Android app for the Packd app.

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


