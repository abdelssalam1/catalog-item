the project is created for udacity's fullstack nanodegree

purpose
this program represents a website that is capable of:
-authenticating user with:
	facebook
	google
-listing general categories that hold specific items that can by displayed with description.
-authorizing user to prevent any user from modifing any category that they didn't create.
-editing categories and items.
-deleting categories and items.
setup:
	in order to run your code, the user will first need to run database_setup.py
	then ryn the main application file project.py

Tools used in development:
	Python 3
	Vagrant
	VirtualBox
	Git

code:
	this project was developed using localhost on port 8000.
	the project's main file	is project.py
	templates are in the templates folder.
	i have two more files the first is client_secrets.json it's used to implement oauth using google
	the other one is fb_client_secrets.json it's used to implement oauth using facebook.
	static folder contains css file.
	
	you will need to sign in in order to create categories , add items edit and delete them

this code was written by Mohamed Abdelsalam 