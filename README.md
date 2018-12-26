# Learning Fullstack JavaScript Development: MongoDB, Node.js, React.js

# Running webpack command to bundle js for client
$ npm run dev

# Configuring database
1. Start mongodb container

2. Change database connection in ./config.js

3. Init test data
3.1 Run script loadTestData.js to init data
3.2 Run script updateTestData.js for update data for using _id field

* Because of the ES6 style in import statement, so that we can not simply run 'node loadTestData.js'. 
Workaround: 

$ ./node_modules/.bin/babel-node loadTestData.js
$ ./node_modules/.bin/babel-node updateTestData.js

# Debug
Suggest using React tab in Google Chrome dev tools

# help links
## MongoDB
https://github.com/mongodb/node-mongodb-native
