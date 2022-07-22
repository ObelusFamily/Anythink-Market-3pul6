# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Clone the repository
2. Now you'll need to install `Docker` use this [guide](https://docs.docker.com/get-docker/)
    - To verify that docker was installed properly use the following commands:
    - `docker -v` and `docker-compose -v`
3. Then run `docker-compose up` to load Anythink's backend and frontend.
4. After the docker was built, let's test that the backend is up and running by pointing your browser to https://localhost:3000/api/ping 
5. Now let's test the frontend and make sure it's connected to the backend by creating a new user on https://localhost:3001/register (don't forget to choose cool nickname!)
### That's it you're all set! 🚀
---