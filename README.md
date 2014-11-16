# Jangle Node/Angular Todo App

A Node app built with MongoDB and Angular.

Node provides the RESTful API. Angular provides the frontend and accesses the API. MongoDB stores like a hoarder.

### Current App can be found on my Heroku at:
[Jangle Todo App](http://jangle.herokuapp.com/)

## Requirements

- [Node and npm](http://nodejs.org)

## Installation

1. Clone the repository: `git clone git@github.com:thomaswicker/jangle`
2. Install the application: `npm install`
3. Start the server: `node server.js`
4. View in browser at `http://localhost:8080`
5. Add a config file with a database.js file which you put the following info:

module.exports = {

	// the database url to connect
	url : 'mongodb://{username}:{password}@ds053140.mongolab.com:53140/2due'
}

You can use Mongolab or any other online mongo service or roll your own.