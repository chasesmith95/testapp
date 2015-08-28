source 'https://rubygems.org'

gem 'rails', '4.0.3'
gem 'sass-rails', '~> 4.0.0'
gem 'execjs'
gem 'twitter-bootstrap-rails'
gem 'bootstrap-sass'

ruby "2.1.2"
group :production do
gem "rails_12factor"
gem "pg"
end
group :development, :test do
     gem "sqlite3"
     # Helpful gems
     gem "better_errors" # improves error handling
     gem "binding_of_caller" # used by better errors
     # Testing frameworks
     gem 'rspec-rails' # testing framework
     gem "factory_girl_rails" # use factories, not fixtures
     gem "capybara" # simulate browser activity
     gem "fakeweb"
     # Automated testing
     gem 'guard' # automated execution of test suite upon change
     gem "guard-rspec" # guard integration with rspec
     # Only install the rb-fsevent gem if on Max OSX
     gem 'rb-fsevent' # used for Growl notifications 
end
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
#gem 'therubyracer', platforms: :ruby 
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
  gem 'sdoc', require: false
end

#gem 'bcrypt-ruby', '~> 3.1.2'
#gem 'unicorn'
#gem 'capistrano', group: :development
#gem 'debugger', group: [:development, :test]
