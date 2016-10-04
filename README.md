# cs-club-calendar-client
Basic client for a CRUD calendar application

Here is a link to this organizations Github Workflow Standards: [Github Workflow Standards](https://github.com/cs-club-appdev/cs-club-calendar-client/wiki/Github-Workflow-Standards)

## Development Dependencies
### Command Line Interface (CLI)
A command line interface is a users interface to a computers operating system.  The command line works by allowing users to entering commands into the prompt and having them be executed by the computer.  Most of the technologies we will use in this project will leverage the command line including Git, Npm, Node, Ember, Express and MongoDB.

This project will focus on using the Unix command line interface.

#### Resources
[Basic Unix Commands](http://mally.stanford.edu/~sr/computing/basic-unix.html)

[List of Commands](https://en.wikipedia.org/wiki/List_of_Unix_commands)

[Codecademy Tutorial](https://www.codecademy.com/learn/learn-the-command-line)

### Git
Git is a version control system.  Below are a list of links on installation, documentation and tutorials. 

#### Resources
[Installation Guide](https://git-scm.com/book/en/v1/Getting-Started-Installing-Git)

[Documentation](https://git-scm.com/documentation)

[Codecademy Tutorial](https://www.codecademy.com/learn/learn-git)

[Git-Scm Tutorial](https://git-scm.com/docs/gittutorial)

[Atlassian Tutorial](https://www.atlassian.com/git/tutorials/what-is-version-control)

### Github
GitHub is a web-based Git repository hosting service, not the version control system itself.  Github takes git to the next level by allowing multiple users to collaborate on the same git repositories.  Github can and should be used as a personal portfolio.  We will be using Github as our medium for organizing our project.

#### Resources
[Guides](https://guides.github.com/)

### JavaScript
This project is going to be written in JavaScript.  JavaScript is a high-level, dynamic, untyped, and interpreted programming language.  Javascript is the language of choice when working in web development.

#### Resources
[Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)

[Codecademy Tutorial](https://www.codecademy.com/learn/javascript)

### Node.js
You need to have Node installed in order to run our application.

#### Resources
[Install with Package Manager](https://nodejs.org/en/download/package-manager/)

[Download directly](https://nodejs.org/en/download/)

### Node Package Manager (NPM)
NPM is a package manager used to install, share, and distribute code; manage dependencies in your projects; and share & receive feedback with others.  Node comes with npm installed so you should have a version of npm.

#### Resources
[Documentation](https://docs.npmjs.com/)

[Tutorial](https://www.tutorialspoint.com/nodejs/nodejs_npm.htm)

## Technologies (Tech Stack)
### MongoDB
The database we are going to be using is a NoSQL database called MongoDB.  MongoDB's data is stored in the form of JSON style documents, which is convienent for web based applications.  There is a Node.js module called mongoose.js that we will be using to interface from our application to our Mongo database.

#### Documentation
[MongoDB](https://docs.mongodb.com/manual/introduction)

[Mongoose.js](http://mongoosejs.com/docs/guide.html)

#### Installation
```bash
npm install mongodb
```

### Express.js
Express is a minimal and flexible Node.js web application framework.  We will be using Express to build the backend of our application.  Express is flexible in that it allows you to define the way you structure your application.

#### Documentation
[Express.js](http://expressjs.com)

#### Installation
```bash
npm install express --save
```

### Ember.js
Ember.js is a JavaScript web framework that we will be using to build the frontend of our application.  Ember.js follows the Model View ModelView (MVVM) Pattern to separate the view the user sees and iteracts with and the backend data model.

#### Documentation
[Ember.js](https://guides.emberjs.com/v2.8.0)

#### Installation
```bash
npm install ember --save
```

### Node.js
Node.js is an event-driven JavaScript runtime environment that allows the creation of web servers.  Node.js is optimized for asynchronous I/O which makes it ideal for the creation of web servers.  Express.js is simply a framework for creating Node.js web applications.

#### Documentation
[Node.js](https://nodejs.org/en/docs)

