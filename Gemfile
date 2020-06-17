source 'https://rubygems.org'
ruby '2.1.5'

# Admin Tools
gem 'activeadmin', '>= 0.6.0'
gem 'meta_search', '>= 1.1.3'

# Baseline Infrastructure
gem 'rails', '5.0.0'
gem 'jquery-rails', '>= 4.4.0'
gem 'pg'
gem 'psych', '~> 2.0.0'

# Operations
gem 'newrelic_rpm', '~> 3.9.0.229'

# Users & Authentication
gem 'bcrypt-ruby', require: 'bcrypt'
gem 'devise', '~> 4.0.0'
gem 'omniauth', '>= 1.1.4'
gem 'omniauth-github', '>= 1.1.0'
gem 'simple_form', '>= 3.2.1'

# Data & Features
gem 'acts-as-taggable-on', '~> 3.4.2'
gem 'friendly_id', '~> 4.0.10'
gem 'geocoder'
gem 'octokit', '~> 3.5.2'
gem 'paperclip', '~> 3.0'
gem 'aws-sdk'

gem 'client_side_validations'
gem 'client_side_validations-simple_form', '>= 3.2.0'

# Test Suite
group :development, :test do
  gem 'rspec-rails', '>= 2.13.0'
  gem 'capybara', '>= 2.2.0'
  gem 'factory_girl_rails', '>= 4.5.0'
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
  gem 'quiet_assets', '>= 1.0.2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 5.0.5'
  gem 'coffee-rails', '~> 4.1.1'

  # Foundation front-end framework
  gem 'compass-rails'
  gem 'zurb-foundation', '~> 4.0.0'
  gem 'uglifier', '>= 1.0.3'
end
