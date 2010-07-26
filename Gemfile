# Edit this Gemfile to bundle your application's dependencies.
source 'http://gemcutter.org'
source 'http://gems.github.com'

gem 'rails', '3.0.0.beta4'

gem 'liquid', '2.0.0'
gem 'bson_ext', '>= 1.0.1'
gem 'mongo_ext'
# gem 'mongoid', :git => 'git@github.com:did/mongoid.git'
gem 'mongoid-locomotive'
gem 'mongoid_acts_as_tree', '0.1.5'
gem 'mongo_session_store', '2.0.0.pre'
gem 'warden'
gem 'devise', '1.1.rc1'
gem 'haml', '3.0.13'
gem 'rmagick', '2.12.2'
gem 'aws'
gem 'mimetype-fu', :require => 'mimetype_fu'
# gem 'formtastic-rails3', :require => 'formtastic'
gem "formtastic", :git => "http://github.com/justinfrench/formtastic.git", :branch => "rails3"
gem 'carrierwave-rails3', :require => 'carrierwave'
gem 'actionmailer-with-request', :require => 'actionmailer_with_request'
gem 'heroku'
gem 'httparty', '0.6.0'
gem 'RedCloth'
gem 'inherited_resources', '1.1.2'
gem 'jeweler'

# Development environment
group :development do
  # Using mongrel instead of webrick (default server)
  gem 'mongrel'
  gem 'cgi_multipart_eof_fix'
  gem 'fastthread'
  gem 'mongrel_experimental'
end

group :test, :development do
  gem "ruby-debug"
end

group :test do
  gem 'rspec-rails', '2.0.0.beta.18'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'cucumber'
  gem 'cucumber-rails'
  gem 'spork'
  gem 'launchy'
  gem 'mocha', :git => 'git://github.com/floehopper/mocha.git'
end