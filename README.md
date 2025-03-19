# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...

# Run Ruby on Rails Project

`logger_thread_safe_level.rb`
`require "logger"`

# run command

`bin/rails server`

# model generating command

`bin/rails generate model model_name colum_name:colum_type`

# DB migrate command

`bin/rails db:migrate // undo the last migration => bin/rails db:rollback`

## Tailwind CSS configuration

`bin/bundle add tailwindcss-ruby`
`bin/bundle add tailwindcss-rails`
`bin/rails tailwindcss:install`
`bin/dev`
