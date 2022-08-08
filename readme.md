# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Prerequisites
Before starting, make sure you have Docker installed and that 
` docker -v`
and 
` docker-compose -v `
both work. 

#### Steps
1. Clone this repo
2. From the root directory, run ` docker-compose up -d `
3. Wait for Docker to build the images and run them automatically
4. Once done, verify the containers are running by executing ` docker ps `
