

## Install

`yarn`

## DB Setup

Copy .env.example to .env and set `DATABASE_URL` and `PORT` to your liking.

## Running locally

`yarn start:dev`

This will set the env var LOCAL to true, which will cause the db connection configuration to use specified local database. 

## running on heroku

When the project is deployed to heroku, the command in your `Procfile` file will be run.
