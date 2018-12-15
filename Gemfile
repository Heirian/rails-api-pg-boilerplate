# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Automatic Ruby code style checking tool. Aims to enforce the community-driven Ruby Style Guide.
  gem 'rubocop', '~> 0.61.1', require: false
  # rspec-rails is a testing framework for Rails 3+.
  gem 'rspec-rails', '~> 3.8', '>= 3.8.1'
  # Code style checking for RSpec files. A plugin for the RuboCop code style enforcing & linting tool.
  gem 'rubocop-rspec', '~> 1.30', '>= 1.30.1'
  # RubyCritic is a tool that wraps around various static analysis gems to provide a quality report of your Ruby code.
  gem 'rubycritic', '~> 3.5', '>= 3.5.2', require: false
  # Brakeman detects security vulnerabilities in Ruby on Rails applications via static analysis.
  gem 'brakeman', '~> 4.3', '>= 4.3.1', require: false
  # bundler-audit provides patch-level verification for Bundled apps.
  gem 'bundler-audit', '~> 0.6.0', require: false
  # Code coverage for Ruby 1.9+ with a powerful configuration library and automatic
  # merging of coverage across test suites
  gem 'simplecov', '~> 0.16.1', require: false
  # factory_bot_rails provides integration between factory_bot and rails 3 or newer
  # (currently just automatic factory definition loading)
  gem 'factory_bot_rails', '~> 4.11', '>= 4.11.1', require: false
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
