# application_name

This app does: ????

## Setup

1. Pull down the app from version control
2. Make sure you have Postgres and Redis running
3. `bin/setup`

## Running The App

1. `bin/run`

## Tests and CI

1. `bin/ci` contains all the tests and checks for the app
1. `tmp/test.log` will use the production logging format
    *not* the development one.

## Production

* All runtime configuration should be supplied
  in the UNIX environment
* Rails logging uses lograge. `bin/setup help`
  can tell you how to see this locally


## Rename your project
1. Open the script `rename.sh`
2. Change `NEW_NAME` & `NEW_CAMEL_NAME` variables with your app name
3. Execute the script `sh rename.sh`
3. Remove the file `rename.sh`
