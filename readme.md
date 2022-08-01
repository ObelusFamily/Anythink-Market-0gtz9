# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To install and run the repo on your local machine, follow the following steps:

1. Make sure docker is installed on your machine. You can find it at [this](https://docs.docker.com/get-docker/) location. Then follow the steps to install it on your machine.
2. Run `docker -v` to check if docker is properly installed on your machine and run `docker-compose -v` to check if docker compose is installed properly.
3. Clone this repository on your local machine.
4. From the project directory, run `docker-compose up` to load Anythink's backend and frontend.
5. If Docker is working correctly, the backend should be running and able to connect to your local database. To test this, point your browser to <http://localhost:3000/api/ping>.
6. To check the frontend, point your browser to <http://localhost:3001/register> and register a new user for yourself.
