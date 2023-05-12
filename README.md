# mern_jokes_api_core

## solution branch

- [ ] Create a project folder named "Jokes"

- [ ] within "Jokes" create a modularized folder structure (server ==> controllers, routes, models, config, server.js)

- [ ] initialize a package json file using npm

- [ ] install `express` and `mongoose`

- [ ] create a `mongoose.config.js` file and set up your `mongoose.connect` function

- [ ] create a `jokes.model.js`, `jokes.controller.js`, and a `jokes.routes.js` in the applicable folders

- [ ] in the `jokes.model` file create a JokeSchema and export the mongoose.model("joke", JokeSchema)

- [ ] in the `jokes.controller` import your model from the models file

- [ ] Export a function to get all jokes

- [ ] Export a function to get a single joke

- [ ] Export a function to create a joke

- [ ] Export a function to update a joke

- [ ] Export a function to delete a joke

- [ ] In the `jokes.routes` file: Set the exported functions from your controller file to a variable using the `require` keyword, then add an express route for every route listed in the wireframe

- [ ] In your `server.js` file: setup express, import your joke routes, and run your server

- [ ] Use Postman to create new jokes and confirm they've been added by using the GET request that returns all the jokes in the collection

- [ ] Use Postman to perform the POST DELETE and PUT operations and confirm the routes work using your GET requests