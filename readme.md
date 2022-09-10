# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Run `docker-compose up` from the project root directory -> if Docker is working correctly, the backend should be running and able to connect to your local database
2. Test this by pointing your browser to http://localhost:3000/api/ping -> you should see the following message `{"msg":"Pong! Seems like Everythink is working, great job!"}`
3. Check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register 
4. Complete the signup -- choose a cool nickname and everything ;)
