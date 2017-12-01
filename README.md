# Splurty

A database-powered quote generator with a mobile-first design using Ruby on Rails, HTML, and CSS.

This app powers Splurty located https://splurty-jared-schilling.herokuapp.com/

## Getting Started

## Software requirements

- Rails 5.0.0 or higher

- Ruby 2.3.1 or higher

- PostgreSQL 9.3.11 or higher

## Navigate to the Rails application

```
$ cd /path/to/rails/application
```

## Set configuration files

```
$ cp config/database.yml.template config/database.yml
```

Note:  You may need to edit the above files as necessary for your system.

## Create the database

 ```
 $ pgstart
 $ rails db:create
 ```

## Migrating the database

```
$ rails db:migrate
```

## Starting the local server

```
$ rails server

   or

$ rails s
```

## Production Deployment

  ```
  $ git push heroku master
  $ heroku run rails db:migrate
  ```

## License

Splurty is released under the [MIT license](https://mit-license.org).

## Copyright

copyright:: (c) Copyright 2017 Jared Schilling. All Rights Reserved.
