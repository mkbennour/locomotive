source 'https://rubygems.org'

gem 'rails', '3.2.3'

gem 'thin'
gem 'devise'
gem 'simple_form'
gem 'settingslogic'

# ActiveAdmin dependencies
gem 'activeadmin'
gem 'formtastic', '2.0.0'
gem 'meta_search'

group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platform => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'twitter-bootstrap-rails'

group :development, :test do
  gem 'sqlite3'

  gem 'debugger'
  gem 'awesome_print'
  gem 'progress_bar'

  gem 'factory_girl_rails'
  gem 'faker'
end

group :development do
  gem 'heroku_san'
  gem 'rails-footnotes'
  gem 'quiet_assets'
end

group :test do
  gem 'rspec'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'launchy'
  gem 'capybara'
  gem 'capybara-email'
end
