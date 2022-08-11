# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker on your machine - [Download Link](https://docs.docker.com/get-docker/)
2. Verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`
3. Navigate to your **project root directory** and run the command `docker-compose up` to start Docker

### Tests
To verify your setup is working, run the following tests:
1. Point your browser to [this address](http://localhost:3000/api/ping). If it loads successfully, the backend is working as expected
2. Navigate to [this page](http://localhost:3001/register) and sign up as a new user to verify the frontend is connected and working as expected

All **done**!