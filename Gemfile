source 'https://rubygems.org'

ruby '2.1.4'

gem 'rails', '4.1.7'
gem 'bcrypt',               '3.1.7'
gem 'sass-rails', '~> 4.0.4'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'bootstrap-sass', '3.2.0'
gem 'sprockets'
gem 'rails-html-sanitizer', '1.0.1'
gem 'polymer-rails'
gem 'polymer-core-rails'
gem 'polymer-paper-rails'


group :doc do
  gem 'sdoc', require: false
end



group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails', '2.13.1'
  gem 'childprocess', '0.3.6'
  gem 'nokogiri'
  gem 'byebug',       '3.5.1'
  gem 'web-console',  '2.0.0.beta3'
  gem 'spring',       '1.1.3'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'rb-notifu', '0.0.4'
  gem 'minitest-reporters', '1.0.5'
  gem 'mini_backtrace',     '0.1.3'
  require 'rbconfig'
  gem 'wdm', '>= 0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw/i
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
  gem 'unicorn',        '4.8.3'
end
