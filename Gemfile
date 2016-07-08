source 'https://rubygems.org'

# Ruby version
ruby '2.2.3'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
# Use sqlite3 as the database for development and test
gem 'sqlite3', group: [:development, :test] #for the group we are passing 
#a two values, development and test

gem 'pg', '~> 0.18.4', group: :production #for the group we are passing one value
#which is production, so no need for brackets since it's just on value

#Add 12 factor for Heroku
gem 'rails_12factor', '~> 0.0.3', group: :production

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

#Use bootstrap for front-end
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.6'

#Use Stripe for e-commerce payments
gem 'stripe', '~> 1.44'

#Figaro gem for securely managing credentials
gem 'figaro', '~> 1.1', '>= 1.1.1'

#Letter opener for emails in development
gem 'letter_opener', '~> 1.4', '>= 1.4.1', :group => :development

