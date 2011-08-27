# Ringo Heroku App

This is a minimal RingoJS application targeting deployment to Heroku.

## Deploy

    $ gem install heroku
    $ heroku create --stack cedar
    $ git push heroku master
    $ heroku open

## Dev

To run it locally launch ringo
with the main script via foreman:

    $ gem install foreman
    $ foreman start

Then point your browser to this URL:

  http://localhost:5000/
