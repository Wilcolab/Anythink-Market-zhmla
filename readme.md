# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install docker using the steps found [here](https://docs.docker.com/get-docker/)
Ensure docker and docker-compose are both installed and functioning:
Docker Check: ```docker -v```
Docker-Compose Check: ```docker-compose -v```

Within the main folder run ```docker-compose up -d``` to spin up the docker containers for the application in a daemon.

Test to ensure it is working by going here: ```http://localhost:3000/api/ping```
Register a new user to ensure it is connected to the backend here: ```http://localhost:3001/register```

To shutdown the app perform ```docker-compose down```
