source "http://rubygems.org"

gem "rails", '3.1.0.rc1'
gem "rails_autolink", "~> 1.0.1"

gem "rake", "~> 0.9.1"
gem "bson_ext"
gem "gowalla"
gem "itunes_parser", :git => "git://github.com/phiggins/itunes_parser.git"
gem "jquery-rails"
gem "kaminari"
gem "mongoid"
gem "mongoid_rails_migrations"
gem "simple-rss", :git => "git://github.com/jasonrudolph/simple-rss.git"
gem "tilt"
gem "twitter"
gem 'whenever', :require => false

# Asset template engines
gem "sass"
gem "coffee-script"
gem "uglifier"

group "development", "test" do
  gem "factory_girl_rails", :require => nil
  gem "faker"
  gem "rspec-rails"
end

group "test" do
  gem "capybara", "~> 1.0.0.beta1"
  gem "cucumber-rails"
  gem "database_cleaner"
  gem "fakeweb"
  gem "growl" # for Guard notifications
  gem "guard-cucumber"
  gem "guard-rspec"
  gem "guard-spork"
  gem "launchy"
  gem "mocha"
  gem "rb-fsevent", :require => false if RUBY_PLATFORM =~ /darwin/i
  gem "spork"
  gem "vcr"
end

# Deploy with Capistrano
gem 'capistrano'
