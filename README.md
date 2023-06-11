# NewsJunkie

NewsJunkie is a news app that keeps you updated on global events. Search for specific topics and get curated news articles. Personalized recommendations ensure you stay informed and discover new stories. Stay connected with the News app for accurate and up-to-date news coverage.

Tech Stack: NodeJS, Express 

API: https://newsapi.org/

## Screenshots 


<img width="1440" alt="Screenshot 2022-05-20 at 1 21 15 PM" src="https://user-images.githubusercontent.com/70855191/169481359-b56e1438-bc58-460a-ad86-1552bb2bf4e7.png">

<img width="1440" alt="Screenshot 2022-05-20 at 1 21 23 PM" src="https://user-images.githubusercontent.com/70855191/169481461-59bec512-8eb5-41af-9799-9993868b7112.png">

<img width="1440" alt="Screenshot 2022-05-20 at 1 20 33 PM" src="https://user-images.githubusercontent.com/70855191/169481563-d46ac95e-23b5-4661-bbd9-23f92a1a2cef.png">
<img width="1440" alt="Screenshot 2022-05-20 at 1 20 47 PM" src="https://user-images.githubusercontent.com/70855191/169481593-6224199c-a27e-4f41-85c3-69fb3b65c39d.png">


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

<img width="867" alt="Screenshot 2022-05-20 at 1 21 55 PM" src="https://user-images.githubusercontent.com/70855191/169484992-880e7000-0095-443f-b128-49cc862edf68.png">


## Dependencies 
* [expressjs](https://github.com/expressjs/express):  The server for handling and routing HTTP requests

## Application Structure 

* server.js - The entry point to our application. This file defines our express server. 
