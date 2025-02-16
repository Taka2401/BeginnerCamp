source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.5'
gem 'mysql2'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks

# gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
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

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'bullet'
  gem 'spring-commands-rspec'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec'
  gem 'rubocop-airbnb'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'rspec-rails'
  gem "factory_bot_rails"
  # Adds support for Capybara system testing and selenium driver
  gem 'selenium-webdriver'
  # # Easy installation and use of chromedriver to run system tests with Chrome
  # gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'webpacker', '~> 5.0'

gem 'devise'
gem 'refile', require: 'refile/rails', github: 'manfe/refile'
gem 'refile-mini_magick'
gem 'refile-s3', github: 'refile/refile-s3', ref: '768d60d4e5e5e6a00a874767018ff8e31b1da3cd'
gem 'webdrivers', '~> 4.0', require: false

gem 'bootstrap', '~> 4.5'
gem 'jquery-rails'
gem 'font-awesome-sass', '~> 5.13'
gem 'kaminari', '~> 0.17.0'
gem 'bootstrap4-kaminari-views'
gem "geocoder"
gem 'jquery-bgswitcher-rails'
gem 'devise-i18n'
gem 'momentjs-rails'
gem "bootstrap4-datetime-picker-rails"
gem "font-awesome-rails"
gem 'enum_help'
gem 'rails-i18n', '~> 5.1'

gem 'dotenv-rails'
group :production do
  gem 'mysql2'
end
