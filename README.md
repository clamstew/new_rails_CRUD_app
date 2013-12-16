Rails CRUD Apps
==================

This is a cheatsheet to create a new rails CRUD app. 

---

# Make it happen

Begin with a new app

	~> rails new appname
	
This will create a new folder that you need to cd into

	~> cd appname/
	
Open up your glorious new app in **Sublime**

	~> subl .
	
---

# Git at it

Go ahead and put it on a repo:

	# this will create the repo locally in that folder
	~> git init
	
	# you may want to go make a new repo on github at this point and 
	# add it as a remote for your local repo you just created
	# replace the caps below with real names
	~> git remote add REMOTENAME https://github.com/URUSERNAME/PROJECT-NAME.git 
	
	# then its just convention to make an initial commit
	~> git commit -m "Initial Commit"
	
	# make a push if you want just to get things going on the online repo
	# Format: ~> git push -u REMOTENAME LOCALBRANCH
	# so assuming you named your remote origin and your on the master branch:
	~> git push -u origin master
	
*NOTE:*
Check out [hub.github.com](http://hub.github.com). After you install hub, it allows you to make a repo from the command line.  Super Awesome!  (Try throwing that **knowledge bomb** out in an interview.)

	# create a repo for a new project
	~> git init
	~> git add . && git commit -m "It begins."
	~> git create -d "My new thing"
	# (creates a new project on GitHub with the name of current directory)
	~> git push -u origin master
	
---	
	
# Think about it

Seriously, step back from you screen and **grab a whiteboard**. 

**What objects are you dealing with?**

What are your requirements that either you or someone else has given you.  Chances are its a little "CRUD"dy. 

Let's say you are making an app that keeps track of restaurants you ate at and you get to rate things.  

**So for example you need:**

* People
* Restaurants
* Star Rating

