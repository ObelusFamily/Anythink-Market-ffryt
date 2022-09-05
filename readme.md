# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
Clone this repo in your local system

## Second setup

Install [Docker](https://docs.docker.com/desktop/install/) and docker compose in your local environment 

## Third setup

After installing docker, change your current directory to Anythink directory run this command 
```
docker compose up
```

 Wait for a while till docker container starts up.

You may verify it by running to check all three containers are running or not.

```
docker ps
``` 


## Fourth setup

Head to http://localhost:3000/api/ping to check if frontend is working fine. If everything works fine you will be able to see a message saying "Pong! Seems like Everythink is working, great job!".

## Fifth setup

Again head to http://localhost:3001/register to see if your backend is up and running. If you are able to create a new profile then your backend is fine. Just create username and password, then you are good to go.

