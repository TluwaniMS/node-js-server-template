# NodeJs Server Template

## About Repository

This template repository is designed to simplify the setup of a basic Node.js server. 

It installs the following dependencies:
* cors 
* dotenv
* express
* helmet
* morgan

Dev dependencies:
* husky
* jest
* nodemon
* prettier
* pretty-quick
* supertest

## Required software:
* Git client
* Latest stable version of NodeJs

## How to set up the project

Setting up a new git project:
* Clone the repo:
* Remove the repo origin
* Add a new repo origin
* Update the `package.json`

Setting up an existing git project:
* Remove the repo origin
* Add a new repo origin
* Pull the remote origin
* Update the `package.json`

## How to run the project

* Step 1:

Switch to the projects root directory and run `npm install` to install the required packages.

* Step 2:

Set port as an environment variable:

```
PORT=X
```

* Step 3:

Run `npm  run dev` to start-up the server and access the end-points on:

```
http://localhost:{PORT}
```

