source 'https://rubygems.org'
#
# Gems included per Listing 9.4.8
#
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'
gem 'bootstrap-sass'

gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'

# Use sqlite3 as the database for Active Record
group :development, :test do
 gem 'sqlite3'
 gem 'rspec-rails'
end

group :assets do
# Use SCSS for stylesheets
 gem 'sass-rails', '~> 4.0.0'
# Use Uglifier as compressor for JavaScript assets
 gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
 gem 'coffee-rails', '~> 4.0.0'
end

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'factory_girl_rails'
  gem 'cucumber-rails', '1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

#Windows specific gems
gem 'rb-notifu'
# gem 'win32console','1.3.2' causes errors in bundle
gem 'wdm'

group :production do
  gem 'sqlite3'
  gem 'rails_12factor'
end

gem 'bcrypt-ruby', '3.0.1'
gem 'certified'
