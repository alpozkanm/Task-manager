
# Task Manager Project

Basic to-do app with simple UI.

Used technologies: Node.js, MongoDB


## Installation

Clone the project first.

```bash
  cd project-folder
  npm install
  brew services start mongodb-community@6.0
  nodemon app.js
```
After you have done with it, don't forget to stop the nodemon and MongoDB services.

```bash
brew services stop mongodb-community@6.0
```
## Environment Variables

To run this project, :80 port should be available to use locally.

Also to use MongoDB, you will need to add the following environment variables to your .env file.

Following variable is just an example, but it refers to 27017 as MongoDB port.

`MONGO_URI=mongodb://127.0.0.1:27017/?directConnection=true&serverSelectionTimeoutMS=2000&appName=mongosh+1.8.0`