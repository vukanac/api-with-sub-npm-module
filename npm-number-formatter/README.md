# Number Formatter (this is only a NPM from **sub directory** Demo)

A small library that adds commas to numbers


## Installation

Will try out with:

    npm install --save git+https://git@github.com:<vendor>/<project>.git/<sub-directory-of-npm-module>/

so in our case:

    npm install --save git+https://git@github.com:vukanac/api-with-sub-npm-module.git/npm-number-formatter/


## Usage

    var numFormatter = require('???<vendor>/<project>/<sub-directory-of-npm-module>');

    var formattedNum = numFormatter(35666);


Output should be `35,666`


## Tests

    npm test


## Contributing

All new functionality or changes must be linted and covered with unit tests.

    npm run lint
    npm test
