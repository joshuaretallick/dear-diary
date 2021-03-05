# Dear Diary blogging app

For this app I wanted to explore the internal workings of a Rails project through a standard CRUD application.

This blogging app has been created without generating any scaffolds or the usual Rails helpers.  So all routes, models, views and controllers we're manually coded by myself which has helped me really delve in to the magic beneath the hood.  This was especially challenging for the authentication side of things, as rather than use the wonderful (it truly is) gem DEVISE, I opted for BCrypt.  By doing this it has made me understand authentication much deeper at the controller level.


## View my app on Heroku
[CLICK HERE](https://secret-meadow-14231.herokuapp.com/)


## Installation Instructions
- Clone Repo to your local machine
- From Command Line enter directory and then run:
```sh
bundle install
yarn
bundle exec rails db:migrate
bundle exec rails server
```
- Then open `http://localhost:3000` in your browser

## Tech-Stack 
```
Ruby-on-Rails
Bootstrap
JQuery
Popper
BCrypt
will_paginate
```
