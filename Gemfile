source 'https://rubygems.org'
ruby '2.0.0'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
  gem 'rails', '4.0.1'

  gem 'bootstrap-sass', '2.3.2.0' # bootstrap resource gem
  gem 'bcrypt-ruby', '3.0.1' # state-of-the-art hash function called bcrypt to irreversibly encrypt the password to form the password hash
  gem 'faker', '1.1.2' # to make sample users with semi-realistic names and email addresses
  gem 'will_paginate', '3.0.4'
  gem 'bootstrap-will_paginate', '0.0.9'

# Use sqlite3 as the database for Active Record
group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.13.1' # in a development environment to have access to RSpec-specific generators, and in test mode in order to run the tests.
  gem 'factory_girl_rails', '4.2.1' # defines a domain-specific language in Ruby, in this case specialized for defining Active Record objects
  gem 'cucumber-rails', '1.4.0', :require => false # alternative for rspec
  gem 'database_cleaner', github: 'bmabey/database_cleaner' # cucumber's utility gem
end

group :test do
  gem 'selenium-webdriver', '2.35.1' # one of Capybara’s dependencies
  gem 'capybara', '2.1.0' # allows to simulate a user’s interaction with the sample application using a natural English-like syntax
end

  gem 'sass-rails', '~> 4.0.0' # Use SCSS for stylesheets
  gem 'uglifier', '>= 1.3.0' # Use Uglifier as compressor for JavaScript assets
  gem 'coffee-rails', '~> 4.0.0' # Use CoffeeScript for .js.coffee assets and views
  gem 'jquery-rails' # Use jquery as the JavaScript library
  gem 'turbolinks' # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
  gem 'jbuilder', '~> 1.2' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', platforms: :ruby

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :production do
  gem 'pg', '0.15.1' # PostgreSQL
  gem 'rails_12factor', '0.0.2'
end

# Use ActiveModel has_secure_password
  # gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
  # gem 'unicorn'

# Use Capistrano for deployment
  # gem 'capistrano', group: :development

# Use debugger
  # gem 'debugger', group: [:development, :test]