source 'https://rubygems.org'

gem 'rails', '4.2.1'
gem 'sqlite3'
gem 'bootstrap-sass', '~> 3.3.5'
gem 'sass-rails', '>= 3.2'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'awesome_print'
gem 'squeel'
gem 'simple_form'
gem 'activerecord-colored_log_subscriber'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'quiet_assets'
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'faker'
  gem 'shoulda-matchers'
  gem 'guard'
  gem 'guard-rspec', require: false
  gem 'guard-bundler'
  # TODO - add guard gems/config from davinci class notes
end

group :test do
end

group :production do
  gem 'rails_12factor'
  gem 'pg'
end

ruby '2.2.2'
