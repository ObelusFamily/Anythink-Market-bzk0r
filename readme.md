# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

To get started make sure Docker is installed running:

```
docker -v
docker-compoose -v
```

Now while being in the App's root directory run:

```
docker-compose up
```

You should now be able to verify our backend and frontend are running as expected.

Backend: [http://localhost:3000/api/ping](http://localhost:3000/api/ping)

Frontend: [http://localhost:3001/register](http://localhost:3001/register)

Go ahead and create a user through the frontend to verify the backend and frontend connection is working as expected

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
