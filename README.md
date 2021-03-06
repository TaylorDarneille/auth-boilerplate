# Node/Express Auth Boilerplate

## Technologies
* [Node](https://nodejs.org/en/): server
* [Express](https://expressjs.com/): web-app framework for Node
* [EJS](https://ejs.co/)/[EJS layouts](https://www.npmjs.com/package/express-ejs-layouts): views/templates
* [PostgreSQL](https://www.postgresql.org/): SQL Database
* [Sequelize](http://docs.sequelizejs.com/): ORM

## Routes
Route table here

## Model
User model info here

## Get it up and running:

1. `npm install` to install dependencies
2. Add a `.env` file with a `SESSION_SECRET`
3. `createdb <database name>` to create a database for this app
4. In the `config.json` file, change the `database` field from `auth-boilerplate` to the name of the database you just created. If your `postgres` database requires a username and password, add these fields as well.
5. Migrate (using `sequelize-cli`, run `sequelize db:migrate`)
6. Run on `localhost:3000` using `nodemon`
