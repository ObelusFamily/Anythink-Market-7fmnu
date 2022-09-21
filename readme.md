# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Instructions

- Install Docker [Get Docker](https://docs.docker.com/get-docker/). Verify that docker is installed successfully `docker -v` and `docker-compose -v`.

- Clone the repository locally `git clone <url-repo>`.

- On the root directory run `docker-compose up` to start backend with the mongo database instance as well as the frontend app.

- Verify that the backend is started and live by visiting `http://localhost:3000/api/ping`

- Verify that the frontend is started and live by visiting `http://localhost:3001/register`, and create your first account! 

