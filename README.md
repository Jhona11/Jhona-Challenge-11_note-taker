# Note Taker
Week-11 Challenge

## Table of Contents
*  [Description](#Description)
*  [Links](#Links)
*  [Screenshots](#Screenshots)
*  [Installation](#Installation)
*  [Usage-Information](#Usage-Information)

##  Description 
This application was developed to provide users with a platform for organizing their thoughts and managing tasks through note storage. It uses Express and JavaScript, employing a json file (db.json) as a pseudo-database for data storage and retrieval. My responsibilities involved creating a backend for the  frontend of the application using Express, enabling users to save, retrieve, post, and delete data through the frontend UI.

## Links

Live URL of Deployed Application: https://jhona-challenge-11-note-taker2.onrender.com/

Live Screen Recording of Application Functionality: 

## Screenshots 
<img width="1470" alt="Screenshot 1" src="/Develop/public/assets/screenshots/Note Taker-1.png">

<img width="1470" alt="Screenshot 2" src="/Develop/public/assets/screenshots/Note Taker-2.jpg">

<img width="1470" alt="Screenshot 3" src="/Develop/public/assets/screenshots/Note Taker-3.jpg">
## Technologies Used

This project is powered by Express.js and Node.js (v16.19.1), using JavaScript as the programming language. It incorporates uniqid and file system modules as dependencies.

## Installation

1. Clone the repo: `git clone git@github.com:Jhona11/Jhona-Challenge-11_note-taker.git`

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, npm install node.js.

4. Once node.js is installed, in the terminal, utilize the command `npm init -y` to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command `npm i` to install the dependencies associated with this application (developers may need to install express and uniqid directly from the command line, to do so the command for express will be `npm i express` to install the latests version of Express framework globally so that it can be used within the node terminal, and `npm i uniqid` to install the latest version of uniqid).

6. To run the server, within the terminal, type the command `node server.js`.

7. Once the server is running, users can then access the front end of the application within the browser to observe full functionality of the site.

## Usage Information

This application requires a server running in the background, which is powered by Express. To start the server, follow these steps:

1. Navigate to the application's directory.

2. Install all dependencies by running the command `npm i`.

3. Start the server by typing `node index.js`.

4. The command line will display a message: "App listening at http://localhost:3001 🚀".

5. Once the server is running, access the application's front end directly from the command line by holding the command key and clicking on the link http://localhost:3001.

6. Users can then view existing notes from the database or create new notes.

7. Any newly created notes will be saved to the database and persisted.
