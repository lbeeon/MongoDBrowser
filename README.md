mongo-express
=============

Web-based MongoDB admin interface written with Node.js and express

[![Build Status](https://secure.travis-ci.org/andzdroid/mongo-express.png?branch=master)](http://travis-ci.org/andzdroid/mongo-express) - Master (stable) branch

[![Build Status](https://secure.travis-ci.org/andzdroid/mongo-express.png?branch=develop)](http://travis-ci.org/andzdroid/mongo-express) - Develop branch


To use:
-----------

* git clone https://github.com/7urkm3n/MongoDBrowser.git
* npm install not necessary
* node app.js
* default: `http://localhost:8081`
* prompt: enter or login (no Username and Password)

For custom port or username and password just visit: `config.js`


Visit `http://localhost:8081` or whatever URL/port you entered into your
config (if running standalone) or whatever `config.site.baseUrl` (if mounting
as a middleware).



Limitations
-----------

* Documents must have `document._id` property to be edited
* No GridFS support (might become a planned feature)
* Binary BSON data type not tested

JSON documents are parsed through a javascript virtual machine, so **the web
interface can be used for executing malicious javascript on a server**.

**mongo-express should only be used privately for development purposes**.


Screenshots
-----------

<img src="http://i.imgur.com/DOi3b.png" title="Viewing documents in a collection" />

Click here for more screenshots:
[http://imgur.com/a/OTZHe](http://imgur.com/a/OTZHe)

These screenshots are from version 0.11.0.

**To use:**

Visit `http://localhost:8081` or whatever URL/port you entered into your
config (if running standalone) or whatever `config.site.baseUrl` (if mounting
as a middleware).


