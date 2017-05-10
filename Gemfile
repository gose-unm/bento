source 'https://rubygems.org'
ruby '2.4.1'

gem 'devise', git: 'https://github.com/plataformatec/devise.git',
              branch: 'master'
gem 'flipflop'
gem 'google-api-client'
gem 'http'
gem 'http_logger'
gem 'jquery-rails'
gem 'jquery-validation-rails'
gem 'kaminari'
gem 'lograge'
gem 'nokogiri'
gem 'omniauth-mit-oauth2'
gem 'omniauth-oauth2'
gem 'puma'
gem 'rails', '5.1.0'
gem 'recaptcha', require: 'recaptcha/rails'
gem 'rollbar'
gem 'sass-rails'
gem 'skylight'
gem 'therubyracer', platforms: :ruby
gem 'uglifier'

group :production do
  gem 'dalli'
  gem 'memcachier'
  gem 'pg'
end

group :development, :test do
  gem 'pry-rails'
  gem 'sqlite3'
end

group :development do
  gem 'annotate'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'listen'
  gem 'rubocop'
  gem 'web-console'
end

group :test do
  gem 'coveralls', require: false
  gem 'minitest-rails'
  gem 'minitest-rails-capybara'
  gem 'minitest-reporters'
  gem 'mocha'
  gem 'simplecov', require: false
  gem 'vcr'
  gem 'webmock'
end
