# Hamburger
 This is a simple full-stack application with a handlebars front end / node + express + mysql back end and an ORM.  

## Usage

User may enter any burger name to add it to the burger menu.  This action also adds the new burger into the MySQL database.  To "eat" the burger, click on it. 

## Install

To run the application locally, first clone this repository with the following command.

	git clone git@github.com:owensource/hamburger.git
	
Next, install the application dependencies.

	cd eat-da-burger
	npm install
	
Finally, run the node server locally.

	node server
	
Now, open the local application on port 3000 at the URL: `http://localhost:3000/`.
