source 'https://rubygems.org'
ruby '2.1.5'

# Admin Tools
gem 'activeadmin', '>= 1.0.0'
gem 'meta_search', '>= 1.1.3'

# Baseline Infrastructure
gem 'rails', '6.1.7.3'
gem 'jquery-rails', '>= 4.4.0'
gem 'pg'
gem 'psych', '~> 2.0.17'

# Operations
gem 'newrelic_rpm', '~> 3.9.0.229'

# Users & Authentication
gem 'bcrypt-ruby', require: 'bcrypt'
gem 'devise', '~> 4.7.1'
gem 'omniauth', '>= 2.0.0'
gem 'omniauth-github', '>= 2.0.0'
gem 'simple_form', '>= 5.0.0'

# Data & Features
gem 'acts-as-taggable-on', '~> 4.0.0'
gem 'friendly_id', '~> 5.0.3'
gem 'geocoder', '>= 1.6.1'
gem 'octokit', '~> 4.6.0'
gem 'paperclip', '~> 5.2', '>= 5.2.1'
gem 'aws-sdk', '>= 1.52.0'

gem 'client_side_validations'
gem 'client_side_validations-simple_form', '>= 9.0.0'

# Test Suite
group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'dotenv-rails'
  gem 'vcr'
  gem 'fakeweb'
end

group :test do
  gem 'shoulda-matchers'
  gem 'simplecov', '~> 0.7.1'
end

# Development helpers
group :development do
  gem 'quiet_assets'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 5.0.8'
  gem 'coffee-rails', '~> 4.2.2'

  # Foundation front-end framework
  gem 'compass-rails'
  gem 'zurb-foundation', '~> 4.0.0'
  gem 'uglifier', '>= 2.7.2'
end
