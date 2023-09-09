source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.7", ">= 7.0.7.2"
gem 'psych', '~> 4'

gem 'resque'
gem 'resque-pool'

# separate group so that it can be easily generated locally with Docker setup
group :assets, :development, :test do
  gem 'i18n-js' # keep this in sync with the JS dependency
end
gem 'fast_blank'
gem 'webpacker'

gem 'ancestry'
gem 'authlogic'
gem 'fx'
gem 'pg'
gem 'scenic'
gem 'scrypt'
gem 'zeitwerk'

gem 'aws-sdk-s3'
gem 'file_validators'

gem 'i18n'
gem 'sort_alphabetical'

gem 'dotenv-rails'
gem 'lograge'
gem 'tzinfo-data'

gem 'bootsnap', require: false

gem 'inline_svg'

gem 'cells-haml'
gem 'cells-rails'
gem 'dry-types'
gem 'roar-jsonapi'
gem 'trailblazer-cells'

gem 'matrix'
gem 'net-imap'
gem 'net-pop'
gem 'net-smtp'
gem 'sorted_set'

group :development, :test do
  gem 'parallel_tests'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rspec'
  gem 'rspec-cells'
  gem 'rspec-json_expectations'
  gem 'rspec-rails'
  gem 'rubocop', require: false
  gem 'rubocop-rspec'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'webmock'
end

group :test do
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'cuprite'
  gem 'factory_bot_rails'
  gem 'rack-test'
  gem 'rails-controller-testing'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'test-prof'
  gem 'valid_attribute'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller' # an optional dependency of better_errors
  gem 'listen'
  gem 'rack-mini-profiler' # After pg
  gem 'vcr'
end

gem 'after_party'
gem 'whenever', require: false

gem 'transloadit'

gem 'nokogiri'
gem 'rubyXL'

gem 'validates_email_format_of', git: 'https://github.com/alexdunae/validates_email_format_of.git'

gem 'honeybadger'

gem 'interactor'
gem 'interactor-rails'

gem 'redis-rails'

gem 'rack-attack'
gem 'rack-cors'
gem 'rack-proxy'

gem 'finite_machine' # remove monkey patch if possible

gem 'jbuilder'

gem 'jwt'

gem 'fast_excel'

gem 'flipper'
gem 'flipper-redis'

gem 'faraday'
gem 'faraday-follow_redirects'
gem 'prometheus-client'

gem 'holidays'

gem 'premailer-rails'

gem 'kaminari'
gem 'kaminari-i18n'

gem 'activerecord-pg_enum'

gem 'activejob-uniqueness'

gem 'rbtrace'

gem 'composite_primary_keys'

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use sqlite3 as the database for Active Record
gem "sqlite3", "~> 1.4"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

gem 'spring'
gem 'spring-commands-rspec'
gem 'webpacker'
gem 'sass-rails'
gem 'tilt'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

