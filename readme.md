# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

#### Prerequisites

- [Install Docker](https://docs.docker.com/get-docker/)

#### Launch Anythink in local environment

Once docker is set up, you can **run the command `docker-compose up` in the project root directory**.

If Docker is working correctly, the backend should be running and able to connect to your local database.

You can test this by **pointing your browser** to [http://localhost:3000/api/ping](http://localhost:3000/api/ping).

#### Create user

If everything is working properly, you can create new user account for yourself on [http://localhost:3001/register](http://localhost:3001/register).

