source 'http://rubygems.org'

gem 'activerecord', '~> 6.1.2.0', '>= 6.1.2.1', require: 'active_record'
gem 'bcrypt'
gem 'pry'
gem 'rake'
gem 'require_all'
gem 'shotgun'
gem 'sinatra'
gem 'sinatra-activerecord', require: 'sinatra/activerecord'
gem 'thin'
gem 'tux'

group :test do
  gem 'capybara'
  gem 'database_cleaner', git: 'https://github.com/bmabey/database_cleaner.git'
  gem 'rack-test'
  gem 'rspec'
end

group :development do
  gem 'sqlite3', '~> 1.4.0'
end

group :production do
  gem 'pg'
end
