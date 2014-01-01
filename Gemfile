source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

gem 'rails-api', '~> 0.1.0'

# Use sqlite3 as the database for Active Record
group :production, :staging do
  gem 'pg'
  gem 'rails_12factor', '~> 0.0.2'
end

group :development, :test do
  gem 'sqlite3'
end

gem 'active_model_serializers', '~> 0.8.1'

gem 'puma', '~> 2.7.1'

group :test do
  gem 'cucumber-rails', '~> 1.4.0', :require => false
  gem 'database_cleaner', '~> 1.2.0'
  gem 'selenium-webdriver'
  gem 'capybara'
end
