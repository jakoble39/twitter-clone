[![Build Status](https://drone.io/github.com/toshimaru/Rails-4-Twitter-Clone/status.png)](https://drone.io/github.com/toshimaru/Rails-4-Twitter-Clone/latest)

## TODO

* Add profile description to User
  * and Favorites feature
* User Slug
  * Edit user
  * Add Test
* Design
* Test of pagination

## Imprementation

Imprementatin is based on [Ruby on Rails Tutorial](http://ruby.railstutorial.org/ruby-on-rails-tutorial-book).

## Features

This application doesn't provide many features in order to keep it simple. Here is the features:

* See timeline
* Post new tweet
* Follow/Unfollow user

## Used gem

* slim
* rspec
* factory_girl
* capybara
* simplecov
* guard
* bootstrap-sass
* faker

See more details on [Gemfile](https://github.com/toshimaru/Rails-4-Twitter-Clone/blob/master/Gemfile).

## Test

    $ bundle exec rspec

## Data reset and creation

    $ bundle exec rake db:reset
    $ bundle exec rake db:populate
    $ bundle exec rake test:prepare
