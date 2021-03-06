source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.10'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jquery-ui-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use Bootstrap
gem 'bootstrap-sass', '~> 3.3.6'
gem 'bootstrap-datepicker-rails'

# Use Facebook authentication
gem 'omniauth-facebook'
# Koala is a Facebook library for Ruby, supporting e.g. the Graph API 
gem "koala", "~> 2.2"

# Use CanCanCan for authorization control
gem 'cancancan', '~> 1.10'

# Use Figaro to set environment variables
gem 'figaro'

# Use Cocoon for dynamic nested forms
gem "cocoon"

# Use Cloudinary to upload images to the cloud
gem 'cloudinary'

# Use HasSecureToken to generate unique random tokens 
gem 'has_secure_token'

# Use ValidatesTimeliness to validate dates, times and datetimes
gem 'validates_timeliness', '~> 4.0'

# Use Data-Confirm Modal to use confirmation modals
gem 'data-confirm-modal'

# Use Axlsx to export to Excel
gem 'rubyzip', '>= 1.2.1'
gem 'axlsx', git: 'https://github.com/randym/axlsx.git', ref: 'c8ac844'
gem 'axlsx_rails'

# Use jQuery HotKeys for WYSIWYG editor
gem 'jquery-hotkeys-rails'

group :development do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'

  # Use Capistrano for deployment
  gem 'capistrano', '~> 3.1'
  gem 'capistrano-bundler', '~> 1.1.2'
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano-rvm'
  gem 'capistrano-passenger'
  
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :production do
  # Use mysql2 as the database for production
  gem 'mysql2', '~> 0.4.0'
end