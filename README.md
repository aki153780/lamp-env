# lamp-env

You can set up lamp environment using docker.

linux(debian)+apache+mysql8.0+php7.3.

apple sillicon (m1) available

# Usage

1. clone this repository.
1. run the command `docker compose up`.
1. create db using command line or mysqlworkbench which you like.
1. write codes in `src` directory.
1. access http://localhost on your browser, then you can see lamp environment was surely installed.

# Note

DB data will be reserved in `lamp-env/docker/mysql/data`.

Save php files in `lamp-env/src`. If `src` directory doesn't exist, make `src` directory at the top of repository directory.

`lamp-env/docker/mysql/data` and `lamp-env/src` files are ignored to git. So you can set up repositories at the directory `src`.
