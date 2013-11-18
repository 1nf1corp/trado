source 'http://rubygems.org'

gem 'rails', '3.2.12'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Production gems
group :production do
  gem 'mysql2'
end

# Development gems
group :development do
    gem 'better_errors'
    gem 'binding_of_caller'
    gem 'meta_request'
    gem 'haml-rails'
    gem 'quiet_assets'
    gem 'rack-mini-profiler'
    gem 'capistrano', '~> 2.15'
    gem 'bullet'
    gem 'haml'
    gem 'rails_best_practices'
    platforms :ruby do
      gem 'capistrano-unicorn', :require => false
    end
end

group :test do
  gem 'factory_girl_rails'
  gem 'capybara'
  # gem 'selenium-webdriver'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
end

group :development, :test do
  # gem 'rspec-rails'
  gem 'pry'
  gem 'sqlite3'
end
# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'jquery-rails'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

platforms :ruby do
  gem 'unicorn'
end

# Authenication
gem 'devise'
gem 'cancan'

# Image uploader
gem 'mini_magick', '~> 3.5.0'
gem 'carrierwave'

# Monitoring
gem 'newrelic_rpm'

# Font set
gem 'font-awesome-rails'

# Administration
gem 'rails_admin'

# Processing
gem 'sidekiq', :require => false
gem 'sidekiq-failures'
gem 'slim'
gem 'sinatra', '>= 1.3.0', :require => nil
gem 'whenever', :require => false

# To use ActiveModel has_secure_password
gem 'bcrypt-ruby', git: 'https://github.com/codahale/bcrypt-ruby.git', :require => 'bcrypt'