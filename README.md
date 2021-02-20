# local-json-server

Built using [json-server](https://github.com/typicode/json-server) for local use.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs inital DB creation script using JSON files in the /data folder, then launches the json server.
Open [http://localhost:3001](http://localhost:3001) to acces the server.

### `npm start:api`

Launches just the json server. Assumes you have an existing db.json database file and you'd like to preserve the data.

## Endpoints

### GET
Generated based on the object passed for DB creation. See database.js for more details.

By default, this project has 3 GET endpoints:

- `/posts` loads posts data
- `/photos` loads photo data
- `/users` loads user data

### PUT/POST
Can be customised in the server.js file.
