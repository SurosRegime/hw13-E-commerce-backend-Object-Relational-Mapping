# hw13
 
// README basically lays everything out for this one.

// sync to database in server.js --> make the app.listen a callback fn inside a .then() after db is synced with sequelize.sync() ---> sequelize.sync().then(() => {app.listen()})

// define the columns in the models according to readme

// **when setting up the relationships, dig in to the many-to-many docs for sequelize -- it is a little bit tricky

// **Product and Tag routes for findAll is a little tricky as well (many to many), stumbling blocks potential here --- read the docs!