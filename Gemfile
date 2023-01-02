source "https://rubygems.org"
ruby ">= 2.2.2"

gem "rails", "~> 7.0.2"
gem "mail", ">= 2.8.a"

# Use Uglifier as compressor for JavaScript assets
gem "uglifier", ">= 1.3.0"
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

gem "activeadmin"
gem "devise"
gem "sassc-rails", "~> 2.1"

gem "faker"
gem "psych", "~> 4.0"

gem "country_select"

group :development do
  gem "erb_lint"
  gem "mechanize","2.8.5"
end

gem "pg", "~> 1.1"

gem "puma", "~> 6.0"

group :production do
  gem "airbrake"

  gem "rack-throttle"
  gem "rack-cache"
end

group :development, :test do
  gem "factory_bot_rails"
  gem "rspec-rails", "~> 5.0"
  gem "rubocop", "1.30.1"
  gem "rubocop-rails", "~> 2.4"
  gem "rubocop-rspec", "~> 2.0"
  gem "importmap-rails"
end

group :test do
  gem "shoulda-matchers"
  gem "webmock", "~> 3.14.0"
  gem "simplecov", :require => false
end

gem "image_processing", "~> 1.12"
