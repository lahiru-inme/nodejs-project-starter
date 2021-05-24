# Nodejs-project-starter

A basic scaffold/skeleton to create a Node.JS Express server.

# Contributing

If you wish to contribute to this repository, please feel free to clone/fork. Issue Pull Requests or open issues for any changes that you make.


## Functionality

- Configurable application variables
- REST-ful API Setup
- MongoDB support


## Folder Structure

```
src
│   index.js        # Entry point for application
└───config          # Application environment variables and secrets
└───controllers     # Express controllers for routes, respond to client requests, call services
└───loaders         # Handles all startup processes
└───middlewares     # Operations that check or maniuplate request prior to controller utilizing
└───models          # Database models
└───routes          # Express routes that define API structure
└───services        # Encapsulates all business logic
└───views           # Pages
└───utils           # Pages 
└───test            # Tests go here
```

## Setup 

- Clone the repo `git clone https://github.com/lahiruramesh/nodejs-project-starter.git`

- Install Dependencies
  1. Install [NodeJs](https://nodejs.org/en/)
  2. Run `npm install`
    

## Starting

- Run the command `npm start` to run the application in localhost
- Run the command `npm test` to run unit testing
 
