# NodeJS Leaderboard

Backend NodeJS service for leaderboard.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- You need to install these on your system first:<br />
- [Node](https://nodejs.org/en/)<br />
- [Mongodb](https://www.mongodb.com)<br />

### Installing

1) Get project from Github<br />
$ git clone https://github.com/aslongassun/nodejs-leaderboard.git<br />
2) Download and install NodeJS and Mongodb
[Node](https://nodejs.org/en/)<br />
[Mongodb](https://www.mongodb.com)<br />
3) Go to project folder and run<br/>
npm init<br/>
npm install express --save<br/>
npm install mongoose --save<br/>
npm install body-parser --save<br/>
4) Config Url to connect to mongodb in db.js
You can use [mLab](https://mlab.com/) as a cloud-hosted service for running MongoDB<br />
By resister an account then create a databsename on mLab, get the Connect URL and put to db.js<br />
5) Run the server
At the project folder run this commandline:<br/>
node server.js
6) Now you can see the server is running<br/>
Express server listening on port 3000
