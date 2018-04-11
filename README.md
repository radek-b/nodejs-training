Node.js course

$npm install
$npm app
$node -v

1. What is Node.js
2. Installing Node.js

3. Node Core
3.1 Global object
	https://nodejs.org/api/globals.html
	global.console.log("Hello world");
	
3.2 Argument variables with process.argv
	https://nodejs.org/api/process.html

3.3 Standard input and standard output
3.4 Global timing functions

4. Node Modules
4.1 Core Modules
4.2 Collecting information with Readline
	https://nodejs.org/api/readline.html
4.3 Handling events with EventEmitter
4.4 Exporting custome modules
4.5 Creating child process with exec
4.6 Creating child process with spawn

5. The File System
5.1 Listing directory files
	https://nodejs.org/api/fs.html
5.2 Reading files
5.3 Writing and appending files
5.4 Directory creation
5.5 Renaming and removing files
5.6 Renaming and removing directories
5.7 Readable file streams
5.8 Writable file streams

6. The HTTP Modules
6.1 Making a request
	https://nodejs.org/api/http.html
	https://nodejs.org/api/https.html
	
6.2 Building a web server
6.3 Serving files
6.4 Serving JSON data
6.5 Collecting POST data

7. Node Package Manager
7.1 Installing npms locally
	https://www.npmjs.com/
	#npm -v
	#npm install underscore
	#npm install async
	#npm ls
	#npm remove async
7.2 Installing npms globally on Mac
7.3 Installing npms globally on PC
	#npm install -g node-dev
	https://www.npmjs.com/package/node-dev
	To install globally - run CMD As an Administrator
	#node-dev app.js
	http://localhost:3000/
	
	#npm install -g jshint
	#jshint app.js
	
7.4 File servers with httpster
	#npm install -g httpster
	#httpster -p 3000 -d ./public
	
	//to remove module globally 
	#npm remove -g httpster
	
8. Web Servers
8.1 The package.json file
	//to create package.json
	#npm init
	
	#npm install express --save  (express has been added to package.json as a dependency)
	
	CORS - Cross Origin Resource Sharing
	#npm install cors --save
	#npm install body-parser --save
	
	//if there is no package node_modules then:
	#npm install
	
	//to remove dependency from package.json:
	#npm remove underscore --save
8.2 Intro to Express
8.3 Express routing and CORS	
8.4 Express post bodies and params

9. WebSockets
9.1 Creating a WebSocket server
9.2 Broadcasting messages with WebSockets
9.3 Creating WebSockets with Socket.IO
	https://caniuse.com/#feat=websockets
	socket.io
	
10. Testing and Debugging
10.1 Testing with mocha and Chai
	https://mochajs.org/
	#npm install -g mocha
	
	//to run tests in directory /test:
	#mocha
	
	#npm install chai --save-dev
	
10.2 Asychronous mocha testing
10.3 Mocking a server with Nock
	#npm install nock --save-dev

10.4 Injecting dependencies with rewire
	https://www.npmjs.com/package/rewire
	#npm install rewire --save-dev
	
10.5 Advanced testing Sinon spies
	http://sinonjs.org/
	#npm install sinon
10.6 Advanced testing Sinon stubs
10.7 Code coverage with Istanbul
	#npm install -g istanbul
	#istanbul cover _mocha
10.8 Testing HTTP endpoints with Supertest
10.9 Checking server responses with Cheerio

11. Automation and Deployment
11.1 Hinting your code with Grunt
	#npm install -g grunt-cli
	#npm install grunt --sav-dev
	#npm install grunt-contrib-jshint --sav-dev
	#grunt
11.2 Converting LESS to CSS with Grunt
	#npm install grunt-contrib-less --save-dev
	
	//add prefixes for different browsers in css file (flex)
	#npm install grunt-autoprefixer --sav-dev
11.3 Bundling client scripts with Browserify
	http://browserify.org/
	#npm install jquery
	#npm install grunt-browserify --save-dev
11.4 Rapid development with Grunt Watches
	#npm install grunt-contrib-watch --sav-dev
	
	#node app.js
	
	//in separate tab
	#grunt watch
	
11.5 Automation with npm
	#npm start
	localhost:3000
11.6 Debugging with NPM
	#npm install
	#grunt
	#node app
	localhost:3000
	
	//to debug:
	#node --inspect app
	
	//debugging in Chrome browser:
	chrom://inspect
	
	#node --inspect -inspect-brk app
	
12. Conclusion
	https://www.mongodb.com/
	https://firebase.google.com/
	https://travis-ci.org/
	hosting app: heroku.com, AWS, google cloud
	

=============================================================================================

Node.js Essential Training (course)

	
https://www.lynda.com/Node-js-tutorials/Making-request/417077/454452-4.html?autoplay=true
-----------
Tell me and I forget. Teach me and I remember. Involve me and I learn.

------------

-kalkulator
-fileserver
- chat on websockets