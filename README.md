# React Routes

Today you're practising building routes in a React app' by creating an [eCommerce app](./images/ebool.gif)! It will also test you, as you'll have to use everything you've learned so far!

## Setup

1. Fork this repository
2. Clone the forked repository onto your local machines
3. In the root directory, type `npm install`, which installs dependencies for the project
4. Finally, type `npm run start`, which starts a development server that runs your website in the browser. That server will reload your website whenever you make any changes to source files

## Instructions

- Start your json-server with `json-server --watch db/db.json -p 4000`
- The `templates` folder has a template for each page you have to build
- **There's a folder with screenshots of each page you have to build**
- The app should have 3 main routes: `products`, `categories`, `basket`
- When a user lands on the app, it should be redirected to the `products` route
- Make sure you have dynamic routes for the products detail page once a user clicks on a product card
- Inside the Categories, each category should lead to a filtered version of the products page
- The `add to basket` button on the Products Details page shout add the item to the basket, and take you to the basket page 

## Tips

- With routes, your URL bar becomes part of your state! Use it to your advantage, by setting up your routes with dynamic parameters

## Extra Challenge

- Create a "404 not found" page that should appear every time that a route doesn't match
- Implement a search bar that on submits should take you to a products page with the results of the search
