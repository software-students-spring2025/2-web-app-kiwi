# Web Application Exercise

A little exercise to build a web application following an agile development process. See the [instructions](instructions.md) for more detail.

## Product vision statement

Our web application empowers users to effortlessly create, store, and manage their recipes in a single, organized space, providing quick access through intuitive search functionality for a seamless cooking experience.

## User stories

[User Stories](https://github.com/software-students-spring2025/2-web-app-kiwi/issues)

## Steps necessary to run the software

Required software:

- install and run [docker desktop](https://www.docker.com/get-started)
- create a [dockerhub](https://hub.docker.com/signup) account

Use Docker Compose to boot up both the mongodb database and the flask app using one command:

- Navigate to app directory which contains `Dockerfile`
- open Docker
- `docker compose up --build` ... add -d to run in detached/background mode.
- Ctrl + C then `docker compose down` when done to stop containers

If port number already use, select different port for `flask-app` or `mongodb` by changing their values in `docker-compose.yml`

View the app in browser:

- open `http://localhost:5001` in preferred web browser (or whatever port number used for host) 

_Note that if any files were edited, container must be stopped then restarted_

## Task boards

[Sprint 1 Task Board Link](https://github.com/orgs/software-students-spring2025/projects/50/)
[Sprint 2 Task Board Link](https://github.com/orgs/software-students-spring2025/projects/69/)
