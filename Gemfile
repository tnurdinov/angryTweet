source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

gem 'rails-api', '~> 0.1.0'

# Use sqlite3 as the database for Active Record
group :production, :staging do
  gem "pg"
end

group :development, :test do
  gem 'sqlite3'
end

gem 'active_model_serializers', '~> 0.8.1'

gem 'unicorn', '~> 4.7.0'

group :test do
  gem 'cucumber-rails', '~> 1.4.0', :require => false
  gem 'database_cleaner', '~> 1.2.0'
  gem 'capybara'
end
