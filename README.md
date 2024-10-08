This project is a MERN-based (MongoDB, Express.js, React.js, Node.js) GitHub replica with custom version control implemented from scratch.

Main Function Points
Replicates the core functionality of GitHub, including code repositories, branches, commits, and version control.
Implements custom version control system from scratch, without relying on existing Git infrastructure.
Provides a web-based interface for users to interact with the GitHub-like platform.
Technology Stack

MongoDB: NoSQL database for storing project data.

Express.js: Web application framework for Node.js, used for building the backend API.

React.js: JavaScript library for building the user interface and frontend components.

Node.js: JavaScript runtime environment for executing the backend code.

bycrypt:it is node module which will decrpyt a sensitive inforation like passwords

I implemented following commands of git hub in this project amd here i brefily explained about thise commands:



git init: This command initializes a new Git repository. It creates a new .git directory in the project folder, setting up all the necessary files for version control. This is typically the first command you run when starting a new project with Git.

git add: This command stages changes in your working directory for the next commit. You can specify individual files or use . to stage all changes. Staging allows you to prepare a snapshot of your changes before committing them to the repository.

git revert: This command is used to undo changes by creating a new commit that reverses the changes made in a specified commit. Unlike git reset, which can alter the commit history, git revert is a safe way to undo changes while preserving the history of the repository.
