# StarWars blog database

Inside the `./entities` directory you will find a `./entities/User.js` class describing an example User database entity (table).

Here is a `4min` video explaining what UML is: [https://www.youtube.com/watch?v=UI6lqHOVHic](https://www.youtube.com/watch?v=UI6lqHOVHic)

We are going to be creating the Entity Relationship Diagram for your StarWars Blog Database, a very similar diagram to this one:

![Starwars Diagram](https://github.com/breatheco-de/exercise-starwars-data-modeling/blob/master/assets/example.png?raw=true)
[Click to open diagram](https://app.quickdatabasediagrams.com/#/d/LxNXQZ)

> 🔥 You can use this FREE tool to practice your diagram for the first time: https://app.quickdatabasediagrams.com/#/d/

## 💻 Instalation

This boilerplate already comes with everything you need: a postgres database, the typescript configuration and the TypeORM configuration.

Every time you want to generate your diagram just type: `$ npm run diagram` and it will print a URL link to your diagram image.

## 📝Instructions

Starty by reading the documentation on [how to create entities using TypeORM](https://typeorm.io/#/entities).

Your Job is to update the `./entities/` directory with the files and code needed to replicate the starwars data model.

The project is using the [TypeORM Node.js library](https://typeorm.io/#/) to generate the database.

- Your project must have a table `User` that will represent your blog users.
- Your blog users will be able to login and save their favorite planets and characters.
- The database should store the user favorites.
- The database should store characters and planets.
- What other tables do you think a blog like this might have?
- What properties should go inside the user? or inside the Character or Favorite table?
- What are the relationships between those tables?
- Please add at least 4 models with all of its properties.
- Generate the diagram.png file at the end by running `$ npm run diagram` on the console.


