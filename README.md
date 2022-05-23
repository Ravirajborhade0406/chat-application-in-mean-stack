# Socket.Io Real-time Chat App | A MEAN stack based Real Time chat application


## Description
Socket.IO Realtime Chat App | A MEAN stack based real time chat applicati

## Features

```
    1). Group Chat. 
    2). One to One chat.
    3). Chat messages saved in mongodb.
    4). Login / Logout feature.
    5). Shows which User is typing  and which user is logged in and logged out.
    6). User connected and disconnected feature.
    7). clean ui and ux.
 ```

## Prerequisites

Git

NodeJs

Socket.IO

NPM

MongoDB



## Running

(Note: these instructions are for Ubuntu Linux based OS. Assuming nodejs, npm and mongodb is already installed).

  running mongodb:
```
    1). Open Terminal and change directory to where mongodb is installed in bin folder.
    2). user@linux: ~/path/to/mongodb/bin $ ./mongod 
    3). press enter database server will start.
```
  unzipping and installing dependencies:
```
    1). Unzip the downloaded file.
    2). Open the extracted folder.
    3). Right click somewhere in folder and select Open in Terminal.
    4). Type Command : npm install and press enter. This will install all dependencies shown in package.json file.
```
  running project:
```
  Step 1: Install all dependencies by : npm install and run node app.js
  Step 2: Sign up @ http://localhost:5000/user/signup
  Step 3: Now you're good to go.
  Step 4: Now Login  @http://localhost:5000/user/login
  Step 5: Now Chat with your friends real fast powered by socket.IO and Nodejs.

```
Als Dockerised this application 

used following commands

sudo apt-get update
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo apt-get install docker-ce docker-ce-cli containerd.io
apt-cache madison docker-ce
sudo apt-get install docker-ce docker-ce-cli containerd.io
sudo apt install docker.io
sudo apt install docker-compose
