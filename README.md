# express api

A simple REST API in Node.js

API Endpoints

| Methods     | Urls             |Description            |
| ----------- | -----------      | -----------        |
| GET         | api/employees    |Get all employees           |
| GET         | api/employees/id |Get a specific employee         |
| POST        | api/employees    |Create a new employee         |
| PUT        | api/employees/id    |Update an existing employee|
| DELETE        | api/employees/id    |Delete an existing employee|

## Quick Start

Clone the repo.

```bash
https://github.com/zagaris/express-api.git
cd express-api
```
Create the .env file.

```bash
DB_URL = localhost/my-employees
TEST_DB_URL = localhost/test-my-employees
PORT = 5000
```
Install the dependencies.

```bash
npm install
```
To start the express server, run the following.

```bash
npm run dev
```

For more details check [Build a Restful CRUD API with Node.js](https://dev.to/zagaris/build-a-restful-crud-api-with-node-js-456b-temp-slug-404377?preview=450a474667db7dff8ac9ce683c445c44b772d1b6f7a48471b113d39885a38c735883b921bf76a6a85f6092e6bf486bff810228f3faac896b7170ce60) and take a look around.


