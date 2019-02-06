# My Personal Blog
- A blog is a discussion or informational website published consisting of discrete, often informal diary-style text entries. Posts are         typically displayed in reverse order, so that the most recent post appears first. My blog consists of soccer articles and in order for it    to fully function there has to be a homepage which will display an overview of what the blog is about, as well as showcasing the top 3       blog posts.

- With my Blog I will be using the CRUD application alongside json servers. CRUD is also a term frequently used in the design of UI (user      interface) and UX (user experience), as many web applications' main functionality involves these four basic functions. JSON is a data        format that consists of key-value pairs in the form of strings. The name/value pairs are separated by a colon and each pair is separated     by a comma.

# Getting Started
- Created my repository and added a READMe.md file.

## npm install express-generator -g
* This is the first command that I ran:

- It creates an environment where the server is made.
- Generic Responses are set, in which form their is need.
- Routing Generic need to set.
- Logging where there is a need.

## express --view=ejs
* This is the second commmand that I use and the following was created:

- bin: / www
- public: / images, javascripts and stylesheets
- routes: / index.js and users.js
- views: / error.js and index.js
- app.js
- package.json

## npm install -g json-server
- creates a db.json file with some data

## json-server --watch db.json
- If you make POST, PUT, PATCH or DELETE requests, changes will be automatically and safely saved to db.json.
- Your request body JSON should be object enclosed, just like the GET output.
- Id values are not mutable. Any id value in the body of your PUT or PATCH request will be ignored. Only a value set in a POST request will    be respected, but only if not already taken.