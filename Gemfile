source 'http://rubygems.org'

gem 'rails', '3.0.9'
gem 'rake', '0.8.7'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'
gem 'inherited_resources'
gem 'airbrake'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19', :require => 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
gem 'unicorn'

group :development, :test do
  gem 'steak'
  gem 'capybara'
  gem 'rspec-rails'
end

group :production do
  gem 'mysql2', '0.2.6'
end
