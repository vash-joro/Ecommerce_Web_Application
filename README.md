
Developing a **ShoppingCart (Ecommerce) Application using Angular8**.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.

## Functionalities

1. Users can view all items when entering the website
2. Items are displayed properly based on the selected department and category
3. Users can search items through search box
4. Support paging if we have too many items
5. Users can see item details by selecting a specific item
6. Users can add items to their shopping carts
7. Users can register/login using using firebase authentication
8. Users can update personal profiles with shipping addresses and other info
9. Users can checkout with Paypal payment gateway

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) installed.

```sh
$ 
$ Restore database file on /database/tshirtshop.sql
$ Configure your firebase configuration on backend application
$ Activate Firebase Authentication Providers
$ cd frontend
$ npm install
$ npm start
$ cd backendd
$ npm install
$ npm start
```

Your frontend app should now be running on [localhost:4200](http://localhost:4200/).
Your backend app should now be running on [localhost:8080](http://localhost:8080/).

All changes in the code will be immediately reflected in your browser by [browser-sync](http://browsersync.io/)
