source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.1'
gem 'mysql2', '>= 0.3.18', '< 0.5'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'therubyracer', platforms: :ruby
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'redis', '~> 3.0'
gem 'bcrypt', '~> 3.1.7'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "haml-rails", "~> 0.9"
gem "bower-rails", "~> 0.10.0"
gem 'devise'
gem 'omniauth-twitter'
gem 'rmagick'
# gem 'jquery-turbolinks'
gem 'localtunnel'
gem "fog"
gem "carrierwave"
gem 'carrierwave_direct'
gem 'carrierwave-aws'
gem 'sidekiq'
gem 'sinatra', github: 'sinatra/sinatra'
gem 'activemerchant'
gem 'less-rails-bootstrap'
gem 'therubyrhino' # JRuby
gem 'twitter-bootstrap-rails', github: 'seyhunak/twitter-bootstrap-rails'
gem "font-awesome-rails"
gem 'simple_form'
gem "figaro"
gem 'metamagic'
gem 'countries'
gem 'credit_card_icons'
gem 'bootstrap_progressbar'
gem 'roadie', '~> 3.1.1'
gem "koala", "~> 2.2"
gem 'omniauth-facebook'
gem 'omniauth-linkedin'
gem  "omniauth-google-oauth2"
gem 'ancestry'
gem 'ffaker'
gem 'faker'
gem 'bootstrap-will_paginate'
gem 'geocoder'
gem "jquery-fileupload-rails"
gem 's3_direct_upload'
gem 'yt', '~> 0.28.0'
gem 'active_type'
gem 'inherited_resources', '~> 1.7'
gem "delayed_paperclip"

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  gem 'capistrano-rails'
  # Access an IRB console on 
  # exception pages or by using 
  # <%= console %> 
  # anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

