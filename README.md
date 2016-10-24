# NEAP Server-Side

This is the server-side of our NEAP App. It's a RESTful API. It serves up JSON.

## Development

1. Set up database
  - create and apply migration
  - create and apply seed
1. set up route config
1. create file in routes folder for that resource
1. add route handlers for that resource
1. Set up knex queries
1. set up env variables
1. add control (optional)

## Deployment

1. Setup Heroku
1. Push to Heroku
1. Setup db: `heroku addons:create heroku-postgresql:hobby-dev`
1. Run migrations
1. Run seeds
1. Heroku restart
