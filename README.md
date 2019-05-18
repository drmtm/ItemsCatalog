#  ITEMS CATALOG PROJECT



## Description
This project is introduced as solution to the items catalog project by Udacity fullstack web development course.
this application is a demonstration of using several web development tools including python,Flask,SQLAlchemy,JSON,SQLLIGHT in addition to HTML5,CSS, AND JAVASCRIPT.
ALSO THIS APPLICATION DEMONSTRATE THE TECHNIQUE OF USING 3RD party authentication using Google oauth2 and facebook authentication.
the project is about several categories and their sub item . all can be created browsed updated and deleted with proper authentication to permet control only to the authenticated owner or creator.



## Requirements
to be able to run the project you will need the following:
- [Vagrant](https://www.vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)
- [Python 3.7](https://www.python.org/)
- [Flask framework](http://flask.pocoo.org/)
- [SQLAlchemy](https://www.sqlalchemy.org)


## Set Up

For an initial set up please follow these 2 steps:

1. Download or clone the [fullstack-nanodegree-vm repository](https://github.com/udacity/fullstack-nanodegree-vm).

2. Find the *catalog* folder and replace it with the content of this current repository, by either downloading it or cloning it - [Github Link](https://github.com/drmtm/ItemsCatalog).


## Usage

Launch the Vagrant VM from inside the *vagrant* folder with:

`vagrant up`

`vagrant ssh`

Then move inside the catalog folder:

`cd /vagrant/catalog`

Then Run the application:

`python project.py`

After the last command you will be able to access the application at this URL:

`http://localhost:5000/`



important notes :

* Facebook authentication will not work unless you contact me to add your username to the testers list.

* It is important that you use *localhost* instead of *0.0.0.0* inside the URL address. That will prevent OAuth from failing.

* JSON API endpoints (only works with GET requests)



JSON Endpoints:

| Request URL | RESULT |
| ------------- |:-------------:|
| /category/JSON| Get all Categories listing |
| /category/X/menu/JSON | LIST ALL ITEMS UNDER CATEGORY WITH ID X WHERE X IS AN INTEGER EQUAL TO THE ID OF THE REQUIRED CATEGORY |
| /category/X/menu/Y/JSON | Get all INFO about an item with id Y from a category with id X where x,y are integer numbers |
|
|
