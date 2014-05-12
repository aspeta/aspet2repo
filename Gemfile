source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.4'

# Use sqlite3 as the database for Active Record
# gem 'sqlite3'
group :production do
  gem 'pg'
end
#loads bootstrap css 3.1.1
  gem 'bootstrap-sass', '~> 3.1.1'

# Faker gem file to generate fake data
  gem 'faker'

group :development do
  gem 'sqlite3'
end
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.2'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

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
# rspec for testing
group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails', '~> 4.0'
end

# adding devise for user authentication
gem 'devise'
# adding figaro
gem 'figaro'
# adding pundit for user authentication
gem 'pundit'
#adding redcarpet for formatting
gem 'redcarpet'
# adding carrierwave and minimagick for image uploads
gem 'carrierwave' 
gem 'mini_magick'

#adding fog for cloud services library and makes uploading to S3 easier s3 is amazon cloud
gem 'fog'

# for pagination
gem 'will_paginate', '~> 3.0.5'
# Use ActiveModel has_secure_password

# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
