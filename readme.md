# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Step 1 : Install Docker

Step 2 : Check Docker version via docker -v and docker-compose -v

Step 3 : Go the root directory via your terminal the one you cloned in the beginning.

Step 4 : Run the command 'docker-compose up', this will load Anythink's backend and frontend.

Step 5 : To check the backend and frontend are running fine run the following links.

Backend  -> http://localhost:3000/api/ping
Frontend -> http://localhost:3001/register

Step 6 : Create a new user on frontend page.

And you're done!
