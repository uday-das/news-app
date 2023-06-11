# NewsJunkie

NewsJunkie is a news app that keeps you updated on global events. Search for specific topics and get curated news articles. Personalized recommendations ensure you stay informed and discover new stories. Stay connected with the News app for accurate and up-to-date news coverage.

Tech Stack: NodeJS, Express 

API: https://newsapi.org/

## Screenshots 

![image](https://github.com/uday-das/news-app/assets/89590597/0f2c9cc3-0cc4-4f74-8ccc-9591063357c2)

## Getting Started

For development, you would need Node.js installed in your enviornment. 

### Node
- #### Node installation

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g
    
After installing node: 

To get the Node server running locally: 

* Clone this repo
* On the command line, navigate to the root directory of your package. cd /path/to/package.
* Initialise the npm by running the following command 

  ```
  npm init 
  ```
  
* After initialising npm, you would need to install express using npm. To install express using npm use the following command 

  ```
  npm install express
  ```
* After installing express, you can start the express server using the following command 

  ```
  node app.js
  ```
  
* After starting the server, you should get a message - "Server is running on port 8080" and your app should be now running at [localhost:8080](http://localhost:8080/)

![image](https://github.com/uday-das/news-app/assets/89590597/41202b69-31ae-4df6-838b-288ed7995ebc)

## Dependencies 
* [expressjs](https://github.com/expressjs/express):  The server for handling and routing HTTP requests

## Application Structure 

* server.js - The entry point to our application. This file defines our express server. 

