# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Step 1: Use ```git clone``` command to clone the repository to your **Local Machine**.

Step 2: Install [Docker](https://docs.docker.com/get-docker) for your machine.

Step 3: Follow through the Setup instructions, It's Easy I know you can do it.

Step 4: To check if Docker is up and running, ```docker -v``` and ```docker-compose -v``` .

Step 5: Browse to the folder where your cloned the repo and ```docker-compose up``` command to build the app.

Step 6: If everything went correct , head over to this link http://localhost:3000/api/ping. It should load the anythink page.

Step 7: To check if Frontend and Backend are connected head over to http://localhost:3001/register. Choose credentials and it should login.

**VOILA** your website is up and running in local machine. You can further use ```docker exec``` commands to play around.

