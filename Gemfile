# README
# Use single quotes to define gems for single style coding
# Write description before each added gem

source 'https://rubygems.org'

gem 'rails', '3.2.9'

# Databases
# gem 'mysql2'
gem 'pg'

gem 'jquery-rails'

# Flexible authentication solution for Rails with Warden
gem 'devise'

# Authorization Gem for Ruby on Rails
gem 'cancan'

# Provides Slim generators for Rails 3
# Slim is a template language whose goal is reduce the syntax to the essential parts without becoming cryptic
# gem 'slim-rails'

# Forms made easy for Rails! It's tied to a simple DSL, with no opinion on markup
gem 'simple_form'

# ClientSideValidations made easy for your Rails v3.1+ applications!
# gem 'client_side_validations'
# gem 'client_side_validations-simple_form'

# Easily include static pages in your Rails app (like About us and other)
# gem 'high_voltage'

# Facebook OAuth2 Strategy for OmniAuth 1.0
# gem 'omniauth-facebook'

# Rails plugin to conveniently handle multiple models in a single form
# gem 'nested_form'

# Enumerated attributes with I18n and ActiveRecord/Mongoid support
# gem 'enumerize'

# Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later
# gem 'resque'

# Rails plugin for sending asynchronous email with ActionMailer and Resque
# gem 'resque_mailer'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# MailChimp Email Markup Layouts
# https://github.com/mailchimp/Email-Blueprints

# Addressable is a replacement for the URI implementation that is part of Ruby's standard library
# gem 'addressable'

# ClientSideValidations for Ruby on Rails and integration with simple_form
# https://github.com/dockyard/client_side_validations-simple_form/wiki/Validations-with-simple_form-Twitter-Bootstrap-integration
# gem 'client_side_validations'
# gem 'client_side_validations-simple_form'

# Your Rails variables in your JS
# gem 'gon'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # Stylesheet Authoring Environment that makes your website design simpler to implement and easier to maintain
  gem 'compass-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', platforms: :ruby

  # Speeds up your Rails 3 assets:precompile by only recompiling changed files
  gem 'turbo-sprockets-rails3'

  # Toolkit from Twitter designed to kickstart development of webapps and sites
  # gem 'bootstrap-sass'

  # Font Awesome, SASS version, with assets pipeline, for Rails 3.1+
  # gem 'font-awesome-sass-rails'

  # For rails scaffold
  # gem 'twitter-bootstrap-rails', require: false

  # Settingslogic is a simple configuration / settings solution that uses an ERB enabled YAML file
  # gem 'settingslogic'

  # Webrat - Ruby Acceptance Testing for Web applications
  # gem 'webrat'

  # Compiles your mustache templates with hogan.js on sprockets and the Rails asset pipeline
  # gem 'hogan_assets'

  # Cross-browser vector graphics the easy way. (raphaeljs.com)
  # gem 'raphael-rails'

  # Modernizr is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser
  # gem 'modernizr'

  # Use handlebars.js templates with the Rails asset pipeline
  # Handlebars.js is an extension to the Mustache templating language
  # gem 'handlebars_assets'
end

group :test do
  # Rails Generators for Cucumber with special support for Capybara and DatabaseCleaner
  # Cucumber - BDD that talks to domain experts first and code second
  gem 'cucumber-rails', require: false

  # Acceptance test framework for web applications
  gem 'capybara'

  # Easy model creation/reference in cucumber - optionally leveraging your factories/blueprints
  gem 'pickle'

  # Collection of RSpec/MiniTest matchers and Cucumber steps for testing email using ActiveMailer or Pony
  gem 'email_spec'

  # Spork is a DRb server for testing frameworks (RSpec / Cucumber) that forks before each run to ensure a clean testing state
  gem 'spork-rails'

  # Guard is a command line tool to easily handle events on file system modifications
  # Guard::LiveReload automatically reload your browser when 'view' files are modified
  # Guard::Spork automatically manage Spork DRb servers
  # Guard::Cucumber automatically runs your features (much like autotest)
  # Guard::RSpec automatically run your specs (much like autotest)
  gem 'guard-spork'
  gem 'guard-livereload'
  gem 'guard-cucumber'
  gem 'guard-rspec'

  # Code coverage analysis tool for Ruby 1.9
  gem 'simplecov', require: false

  # RSpec-compatible one-liners that test common Rails functionality
  gem 'shoulda-matchers'

  # Rails: 2 CPUs = 2x Testing Speed for RSpec, Test::Unit and Cucumber
  # gem 'parallel_tests'
end

group :development do
  # Mutes assets pipeline log messages
  gem 'quiet_assets'

  # A rails plugin/gem to kill N+1 queries and unused eager loading
  gem 'bullet'

  # Pure-Ruby Readline Implementation
  gem 'rb-readline'

  # Tiny, fast & funny HTTP server
  gem 'thin'

  # Annotate ActiveRecord models as a gem
  gem 'annotate', git: 'git://github.com/Rezonans/annotate_models.git'

  # Better error page for Rails and other Rack apps
  gem 'better_errors'

  # gem 'disable_assets_logger'

  # For improving performance in dev mode
  # gem 'rails-dev-boost'

  # Deploy with Capistrano
  # gem 'capistrano'
  # gem 'capistrano-ext'
  # gem 'rvm-capistrano'
  # gem 'capistrano_colors'
end

group :development, :test do
  # Fixtures replacement with a straightforward definition syntax
  gem 'factory_girl_rails'

  # Fast Faker == Faker refactored
  gem 'ffaker'

  # A collection of tweaks to improve your Rails (3.1+) development experience.
  gem 'rails-dev-tweaks'

  # Rspec - Behaviour Driven Development framework for Ruby
  # rspec-rails needs to be in the development group so that Rails generators work
  gem 'rspec-rails'

  # Strategies for cleaning databases in Ruby. Can be used to ensure a clean state for testing
  gem 'database_cleaner'
end

group :production do
  #Rack HTTP server for fast clients and Unix
  gem 'unicorn'

  # Allows you to easily perform backup operations
  gem 'backup', require: false
end
