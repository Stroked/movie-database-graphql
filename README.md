# The Movie Database GraphQL wrapper

This is a super simple wrapper of the REST API for [The Movie Database](https://www.themoviedb.org/) to convert it to GraphQL.

Check out the [live API hosted on Heroku](https://movie-database-graphql.herokuapp.com/graphiql).

## Expanded example from @agustif

@agustif has expanded this example and added a lot of different kinds of data! Check it out here: [agustif/movie-database-graphql](/https://github.com/agustif/movie-database-graphql)

## Running the app

You'll need two API keys:

1. [themoviedb.org API key](https://www.themoviedb.org/documentation/api)
2. [Apollo Engine API key](https://engine.apollographql.com/)

Run the app with:

```sh
npm install
TMDB_API_KEY=<key 1> ENGINE_API_KEY=<key 2> npm start
```

## Docs

To learn about what's going on, check out the docs for the tools and libraries used:

1. [Apollo Server](https://www.apollographql.com/docs/apollo-server/)
2. [Apollo Engine](https://www.apollographql.com/docs/engine/)
