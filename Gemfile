source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.6'

# Ruby on Rails
gem 'rails', '~> 6.1'

# ActiveRecord
gem 'pg'

# Infrastructure
gem 'puma'
gem 'bootsnap'
gem 'rack-attack'
gem 'rack-cors'

# Assets
gem 'sass-rails'

gem 'turbolinks'

# Solidus
gem 'solidus_core'
gem 'solidus_api'
gem 'solidus_backend'
gem 'solidus_sample'
gem "solidus_starter_frontend", git: 'https://github.com/nebulab/solidus_starter_frontend'
gem "solidus_user_guides", git: 'https://github.com/seand7565/solidus_user_guides'
gem "solidus_paypal_commerce_platform", git: 'https://github.com/nebulab/solidus_paypal_commerce_platform'
gem "solidus_graphql_api", git: 'https://github.com/solidusio-contrib/solidus_graphql_api'

# Use rspec for testing
gem 'rspec-rails'

# Bootstrap
gem 'bootstrap', '~> 4.4.1'
gem 'jquery-rails'

group :development, :test do
  # Debugging
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rb-readline'
  gem 'binding_of_caller'
  gem 'pry'
end

group :development do
  # Debugging
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
end

group :test do
  # System testing
  gem 'capybara', '>= 2.15'
  gem 'apparition'
  gem 'factory_bot'
  gem 'rspec_junit_formatter'
end

group :production do
  # Infrastructure
  gem 'cloudinary', '~> 1.11'
  gem 'paperclip-cloudinary'

  # Error monitoring
  gem "sentry-raven"
end
