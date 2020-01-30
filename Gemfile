source 'https://rubygems.org'

gem 'rails', '>=4.2.0'

# Use SCSS for stylesheets
gem 'sass-rails', '>= 4.0.3'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '>= 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '>= 2.0'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '>= 0.4.0', group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring', group: :development

# Enables Slack notifications
gem 'slack-notifier'
# E-mail autolab-dev on exceptions in production, pulls the latest to get slack notifications
gem 'exception_notification', git: 'https://github.com/smartinez87/exception_notification.git'

# Used by lib/tasks/autolab.rake to populate DB with dummy seed data
gem 'rake', '>=10.3.2'
gem 'populator', '>=1.0.0'

# To communicate with MySQL database
gem 'mysql2'
gem 'sqlite3'

# Development server
gem 'thin'

# External authentication
gem 'devise', '>=3.3.0'
gem 'omniauth', '>=1.2.2'
gem 'omniauth-facebook', '>=2.0.0'
gem 'omniauth-google-oauth2', '>=0.2.5'
gem 'omniauth-shibboleth', '>=1.1.2'

# Adds It also adds f.error_messages and f.error_message_on to form builders
gem 'dynamic_form'

# Supports zip file generation.
gem 'rubyzip'

# Enables RSpec testing framework with Capybara and Factory Girl.
gem 'rspec-rails'
gem 'rack-test'
gem 'capybara', group: [:development, :test]
gem 'factory_girl_rails', group: [:development, :test]
gem 'database_cleaner', group: [:development, :test]
gem "codeclimate-test-reporter", group: :test, require: nil

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Dates and times
gem 'momentjs-rails', '>= 2.9.0'
gem 'bootstrap3-datetimepicker-rails', '~> 4.0.0'

# Force SSL on certain routes
gem 'rack-ssl-enforcer'

group :development do
  # Better Error Pages
  gem 'better_errors'
  gem 'binding_of_caller' # enhances better_errors

  # Useful debugger
  gem 'byebug', '>=3.5.1'

  # static code analyzer
  gem 'rubocop', require: false
end

# LDAP Lookup
gem 'net-ldap'
