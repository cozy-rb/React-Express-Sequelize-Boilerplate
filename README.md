# React-Express-Sequelize-Heroku
A Heroku-ready boilerplate that uses the following technologies:
- React
- Express
- Sequelize

# Setup
Heroku's config vars should be edited to match the variables stored in .env and their values to match your resource's specific values. A .env.local file can be created if running locally.

Sequelize models should be stored in the /server/database/models folder and required in the models array in the /server/database/services/ModelLoaders.js folder.

# Running
To run locally use:
````
npm run dev
````
