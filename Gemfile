ruby '2.3.1'
source 'https://rubygems.org'

gem 'pg'
gem 'puma', '~> 3.0'
gem 'rails', '~> 5.0'
gem 'rake'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'dotenv'
  gem 'rspec-rails'
  gem 'simplecov'
end

group :development do
  gem 'listen'
  gem 'spring'
end

group :test do
  gem 'cucumber-rails', require: false
  gem 'database_cleaner'
end

group :production do
  gem 'lograge'
  gem 'rails_12factor'
end
