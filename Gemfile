# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "~> 3.0.0"

gem "rails", "~> 6.1.3" # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'

gem "action_policy", "~> 0.5" # Authorization
gem "bootsnap", "~> 1.4", require: false # Reduces boot times through caching; required in config/boot.rb
gem "cable_ready", "~> 5.0.0.pre7"
gem "devise", "~> 4.8" # Authentication

# Dry gems
gem "dry-initializer", "~> 3.0"
gem "dry-initializer-rails", "~> 3.1" # Allow initializers to take in ActiveRecord types

gem "image_processing", "~> 1.2" # Use Active Storage variant
gem "jbuilder", "~> 2.7" # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem "oauth2", "~> 1.4" # OAuth...duh
gem "pg", "~> 1.1" # Use postgresql as the database for Active Record
gem "puma", "~> 5.0" # Use Puma as the app server
gem "stimulus_reflex", "~> 3.5.0.pre7"
gem "redis", "~> 4.0" # Use Redis adapter to run Action Cable in production
gem "redis-session-store", "~> 0.11" # Session store...for Redis
gem "turbo-rails", "~> 0.8.3" # Turbo helpers
gem "tzinfo-data", "~> 1.0", platforms: %i[mingw mswin x64_mingw jruby]
gem "view_component", "~> 2.45"
gem "vite_rails", "~> 3.0" # Transpile app-like JavaScript


group :development do
  gem "brakeman", "~> 5.0", require: false # Security
  gem "listen", "~> 3.3", require: false # Listen to file changes
  gem "memory_profiler", "~> 1.0" # Profiling
  gem "rack-mini-profiler", "~> 2.0", require: false # Profiling
  gem "ruby-prof", "~> 0.16" # More profiling
  gem "stackprof", "~> 0.2", require: false # Profiling
  gem "standardrb", "~> 1.0", require: false
  gem "web-console", ">= 4.1.0" # interactive console on exception pages or by calling 'console'
end

group :test do
  gem "byebug", platforms: %i[mri mingw x64_mingw] # Call 'byebug' anywhere to stop execution and get a debugger console
  gem "capybara", ">= 3.26" # Adds support for Capybara system testing and cuprite driver
  gem "cuprite" # CDP based browser driver
  gem "evil_systems" # System test helpers
  gem "faker", "~> 2.16", ">= 2.16"
  gem "webmock", "~> 3" # Mock HTTP calls
end
