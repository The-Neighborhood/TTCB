# TTCB
A webapp for Thats Too Cute Boutique

# How to Run Locally

This is a very early guide. A lot of information is missing and will need to be added

- install ruby
- install rails
- bundle install (to install all other project dependancies)
- install postgres
  - https://postgresapp.com/
  - https://devcenter.heroku.com/articles/heroku-postgresql#local-setup
- make sure postgres is properly configured by running `rake db:setup` and `rake db:migrate`
- start your local rails server with `rails s`

if everything went smoothly (and it probably didn't...) you should be able to load
http://localhost:3000/
