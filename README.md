# React Pizza Parlor

Group project created using React, Express, Node, and PostgreSQL. User is allowed to order pizzas and checkout.

## Built With

axios, material-ui, postgresql, react, redux, express, node.js

## Getting Started

```sql
CREATE DATABASE "pizza_parlor";

CREATE TABLE "pizza" (
  "id" serial primary key,
  "name" varchar(120),
  "description" varchar(480),
  "cost" numeric
);

CREATE TABLE "order" (
  "id" serial primary key,
  "customer_name" varchar(120),
  "order_total" numeric
);
```

```
npm install
npm run server
```

Now that the server is running, open a new terminal tab with `cmd + t` and start the react client app.

```
npm run client
```

### Prerequisites

- [Node.js](https://nodejs.org/en/)
- [React.js](https://reactjs.org/)
- [postgresql](https://www.postgresql.org/docs/)
- [material-ui-next](https://material-ui-next.com/)


### Completed Features

- [x] Get route to database
- [x] Post route to database
- [x] sagas implemented
- [x] logger implemented
- [x] reudx implemented
- [x] database data appearing on DOM
- [ ] Post to database from client

### Next Steps

Features that you would like to add at some point in the future.

- [ ] Be able to create users and place orders by user.
- [ ] Save past orders per user.

## Deployment

Add additional notes about how to deploy this on a live system

## Authors

* Sarah Bloom
* Ian Carthey
* Teagan Nouska


## Acknowledgments

* Thanks to PrimeAcademy for the base project
