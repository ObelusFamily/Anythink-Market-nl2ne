# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Install Docker
Docker is a container system for running this program. To install Docker [click here](https://docs.docker.com/get-docker/).
Check docker installation with following commands:
```docker -v```
```docker-compose -v```
### Running Program

Run the program using :
``` docker-compose up```
Ok. That’s a great first step - now we can make sure that the code is working :)

### Backend
If Docker is working correctly, the backend should be running and able to connect to your local database.

Test this by pointing your browser to 
```http://localhost:3000/api/ping```

### Frontend
Now, it’s time to check the frontend and make sure it’s connected to the backend.

If everything is working properly, you’ll be able to create a new user on 
```http://localhost:3001/register```