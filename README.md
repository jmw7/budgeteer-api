# Budgeteer

## Introduction
Budgeteer is an experimental React application for expense tracking. 
Budgeteer utilizes authentication for accounts, allowing users to categorize, date and record expenses.

![Home Page](./images/home.png)

#### Click [here](https://budgeteer-app.now.sh/) to test out the app 

### How it works
There is a landing page for all first time and returning users. Any new users can register with a username and password.
Returning users can input their credentials to return to their protected account. 
Adding a transaction pops up a modal that asks for a category, date, cost, and optional payees and memos for the transaction.

![Login](./images/login.png)

![Account Page](./images/account.png)

![Add Transaction](./images/add-transaction.png)


## Getting Started with the Client
### Installing
Clone the repository and download dependencies.
```
$ git clone https://github.com/jmw7/budgeteer-client.git
$ cd recipe-client
$ npm install
```

### Launching
Start development server
```
$ npm run dev
```
This will automatically open a browser window with the project

### Testing
Run tests with Jest and Enzyme
```
$ npm run test
```

## Database
To access the database use the URL below to connect to the client
 - https://calm-taiga-41329.herokuapp.com

### Methods
  GET || POST || DELETE

### Parameters
 - /api/authentication
 - /api/users/
 - /api/:accountId

### Response
 - Post success response: 201
 - Delete success response: 204
 - Post error response: 400
 - Authentication errror response: 401
 - Not found error response: 404

## Built with
 - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
 - [React](https://reactjs.org/)
 - [Node.js](https://nodejs.org/en/)
 - [PostgreSQL](https://www.postgresql.org/)
 - [Knex.js](http://knexjs.org/)
