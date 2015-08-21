# tempuhs demo

A timeline visualisation client that demonstrates 
[tempuhs](https://secure.plaimi.net/works/tempuhs.html).

## Usage

Install dependencies:

    $ npm install

Build required files:

    $ ./node_modules/.bin/gulp

Command can be safely exited after task `default` is finished.

To start the server:

    $ node ./src/server/server.js

### Tempuhs-Server

The client will send requests for timespans to `localhost:7070`. If you want
it to function, there should probably be something at that endpoint
which can handle the requests.

## License

This service is AGPL licensed. See [license](LICENSE)
