source 'https://rubygems.org'

gem 'rails', '~> 4.0', '>= 4.0.0'

# you may comment out the database driver you will not be using.
# This will prevent a native build of the driver. Building native drivers is not 
# always possible on all hosters
gem "sqlite3"
#gem "mysql2"

gem "RedCloth"
gem "formatize"
gem "sanitize"
gem "will_paginate"
gem "acts_as_list"
gem "aasm"
gem "htmlentities"
gem "swf_fu", ">= 2.0.3"
gem "rails_autolink", ">= 1.1.0"
gem "cache_digests"
gem "rack-mini-profiler"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '>= 4.0.0'
  gem 'coffee-rails', '>= 4.0.0'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer'

  gem 'uglifier'
end

gem 'jquery-rails', '>= 2.2.1'

# To use ActiveModel has_secure_password
gem 'bcrypt-ruby'

group :development do
  gem "yard"
  gem "tolk"
  gem "bullet"
end

group :test do
  gem "factory_girl_rails", ">= 4.2.1"
  gem "capybara"
  gem "cucumber-rails", :require => false
  gem "rspec-expectations"
  gem "database_cleaner"

  # aruba 0.5 conflics with newer gems
  # gem "aruba", :require => false
  gem "simplecov"
  gem "timecop"

  # Note that > 2.14 has problems, see: 
  # https://code.google.com/p/selenium/issues/detail?id=3075
  gem "selenium-webdriver" 
  
  # uncomment to use the webkit option. This depends on Qt to be installed
  # gem "capybara-webkit"
  
  # uncomment to be able to make screenshots from scenarios
  #gem "capybara-screenshot"
  #gem "launchy"
end
