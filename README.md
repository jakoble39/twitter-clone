# Rails Twitter Clone

Simple Twitter clone using Ruby on Rails 6.

![Twitter Clone Screen Capture](https://user-images.githubusercontent.com/803398/154789978-e2a4c50d-150b-4d21-885a-81209fc6893e.png)

## Supported Ruby version

- v3.2
- v3.1
- v3.0
- v2.7

## Setup

Check out this repository and then,

```console
$ bin/setup
```

### Start Rails server

```console
$ bin/rails server
```

## Features

This application doesn't provide many features in order to keep it simple. Here are the features that it does include:

- See TimeLine
- Post new Tweet with image
- Follow/Unfollow User
- Edit user profile

## Used gem

### JavaScript

- webpacker
- @rails/ujs

### CSS

- bootstrap (v5)

### Database

- sqlite3

### For testing

- rspec
- capybara
- factory_bot
- faker
- simplecov

### For debugging

- bullet
- debug
- rack-mini-profiler
- rubocop
- web-console

See more details on [Gemfile](./Gemfile).

## Testing

```console
$ bundle exec rspec
```

## Data reset and sample data creation

```console
$ bin/rails db:reset    # Data reset
$ bin/rails db:populate # Create sample data
```
