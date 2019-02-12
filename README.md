# API with NPM module (tryout)

The repo contains a sample API server with only one JSON endpoint,
but also contains a sub directory with full NPM module used in
a frentend JS or NodeJS scripts as a client side to get the data
from API server.

## API server

This can be any, we use a plain PHP file just to be different lang
than NPM module (JS).

## NPM module

A simple client module for accessing API data without worring aboiut
placing HTTP requests, authentication, etc.

Writen in sub directory, with JavaScript, it must contain a
.

This is tryout example how to get an NPM module hosted on GitHub as
a sub directory.

    npm install --save git+https://git@github.com:<vendor>/<project>.git/<sub-directory-of-npm-module>/

# API with NPM module (tryout)

The repo contains a sample API server with only one JSON endpoint,
but also contains a sub directory with full NPM module used in
a frentend JS or NodeJS scripts as a client side to get the data
from API server.

## API server

This can be any, we use a plain PHP file just to be different lang
than NPM module (JS).

## NPM module

A simple client module for accessing API data without worring aboiut
placing HTTP requests, authentication, etc.

Writen in sub directory, with JavaScript, it must contain a
`package.json`.

This is tryout example how to get an NPM module hosted on GitHub as
a sub directory.

    npm install --save git+https://git@github.com:<vendor>/<project>.git/<sub-directory-of-npm-module>/

