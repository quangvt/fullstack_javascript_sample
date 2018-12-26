# learn-fullstack-javascript
Learning Fullstack JavaScript Development: MongoDB, Node.js, React.js

# run webpack command to bundle
$ npm run dev

# Database configuration
1. Start mongodb container

2. Change database connection in ./config.js

# Init test data
1. Run script loadTestData.js
2. Run updatdTestData.js for using _id field

Because of the ES6 style in import statement, so that we can not simply run 'node loadTestData.js'. 
Workaround: 

$ ./node_modules/.bin/babel-node loadTestData.js

# Try by devtools (eg: google devTools)
> $r.setState({ contests: $r.state.contests.slice(1) })

# MongoDB help
https://github.com/mongodb/node-mongodb-native
