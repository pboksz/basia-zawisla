ruby '2.2.0'
source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
gem 'font-awesome-sass'
gem 'compass-rails'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Use haml for views
gem 'haml-rails'

group :development do
  gem 'travis'
end

group :production do
  gem 'heroku-deflater'
  gem 'rails_12factor'
end

group :development, :production do
  gem 'unicorn'
end
