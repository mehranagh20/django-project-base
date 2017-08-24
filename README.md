_Django Takeoff_
===
**Django** necessary materials and examples for begginers to start from zero and takeoff to learn more.

---

_Who is it for?_
===
Everyone wish to start learning django.

_Table of contents_
===
* [**Overview of python**](#overview-of-python)
* [**About web**]()
	* Overview
	* Backend web development
	* Frontend web development
* [**Virtual environment**](#virtual-environment)
	* Overview
	* Why bother using it?
	
* [**What is django**?]()
	* Overview
	* Installation
	* Django follows MVC pattern
  
* [**Development tools and IDEs**]()
* [**Starting a django project**]()
	* What is an app?
	* When and why to use apps?
	* Create an app
* [**Views**]()
	* Overview
	* Django URL scheme
	* Exception handling
	* Decorators
* [**Templates**]()
	* Overview
	* Views and templates.
	* Django template system.
	* Variables and filters.
* [**Models**]()
	* Overview
	* Fields
	* Migration
	* Queries and filters
* [**Forms**]()
	* Overview
	* Validation
* [**Authentication and security**]()
	* Django authentication system
	* CSRF protection
* [**Django admin site**]()
	* Overview
	* Customize
* [**Djagno Unit testing**]()
	* What is testing?
	* Waste of time?
* [**Django and RESTfull web development**]()
* [**LONG ROAD AHEAD**]()

Overview of python
===
## Necessary materials to know

* python uses no semicolon and braces but intendation
* defining variables
* if, for, while syntax
* list, map, tuples usage
* functions declaration
* classes declaration
* Exception handling
* import statement
* python package manager

Virtual Environment
===
## Overview
By default, installing packages and tools with python package manager will install it in global site-package directory, _the whole system_, this will be a problem soon enough so we use some tools called Virtual Environment tools.

> A Virtual Environment is a tool to keep the dependencies required by different projects in separate places, by creating virtual Python environments for them. It solves the “Project X depends on version 1.x but, Project Y needs 4.x” dilemma, and keeps your global site-packages directory clean and manageable.

Python has a virtual environment tool called virtualenv.

## Why bother using it?
Projects Dependencies become more and more complicated over time.

You may not feel needing a Virtual Environment tool at the first but over time, the bigger projects get and the more projects you involve in, it will feel like hell managing dependencies of projects.

A lot of these problems can be solved with a proper Virtual Environment tool like virtualenv.
