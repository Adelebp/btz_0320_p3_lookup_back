# Look Up API

## Pre-requisite

- node 12.16.3
- npm 6.14

## Getting started

- git clone
- npm install
- npm run dev : Start local development server using nodemon
- create an .env file at the root of the folder to be able to connect to your database
  - exemple file .env :
    - DB_HOST=localhost
    - DB_USER=toto
    - DB_PASSWORD=superpassword
    - DB_DATABASE=api_test
    - DB_DIALECT=mysql
    - DB_TEST=test

## Execution and writing of tests

- npm test : Start test server using mocha
- Using Chai and Chai-http with method _should_

## Curious behavior

- importing a route in a model will crash or not validate your tests

## Autors

`Marc , Adèle, Jp, Tommy, Marion`
