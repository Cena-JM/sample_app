# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails',                    '~> 5.2.3'
gem 'bcrypt',                   '3.1.12'
gem 'bootstrap-sass',           '3.4.1'
gem 'faker',                   '1.7.3'
gem 'carrierwave',             '1.2.2'
gem 'mini_magick',             '4.7.0'
gem 'will_paginate',            '3.1.6'
gem 'bootstrap-will_paginate',  '1.0.0'

# Use sqlite3 as the database for Active Record
group :development, :test do
  gem 'sqlite3', '~> 1.3.13'
end # Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.6'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 3.2.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2.2'
# Custome add gem Uglifier by James Okunalde
gem 'jquery-rails', '~> 4.3.1'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5.0.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7.0'
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

group :production do
  gem 'pg',  '0.20.0'
  gem 'fog', '1.42'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'listen', '>= 3.1.5', '< 3.2'
  gem 'web-console', '>= 3.5.1'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '>= 2.0.2'
  gem 'spring-watcher-listen', '~> 2.0.1'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'rails-controller-testing'
  gem 'selenium-webdriver'
end
