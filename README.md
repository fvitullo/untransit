
## Install and run

In order to install dependencies and start the server, type the follwing commands

    $ npm install
    $ bower install
    $ node server.js

Now the app is running at http://localhost:8080

## Setting GTFS dataset

GTFS files are located in directory /public/data

GTFS files are grouped by cities. At the moment, you can select just one city dataset.

You can choose which dataset to use changing app config file
in /js/config/options.js

    define({
      'dataset':'pavia'
    });

You need to specify the name of the directory where your dataset is.

## Examples

Show all stops

    http://localhost:8080/stops/

Show stop pv0101 (Pavia dataset)

    http://localhost:8080/stops/pv0101

## Credits

Built with [Chaplin.js](http://chaplinjs.org)
