# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

gem "rails", "~> 7.0.4", ">= 7.0.4.3"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "bootsnap", require: false
gem "rubocop-shopify", "~> 2.13"

group :development, :test do
  gem "debug", platforms: [:mri, :mingw, :x64_mingw]
  gem "byebug", "~> 11.1", ">= 11.1.3"
  gem "rspec-rails", "~> 6.0", ">= 6.0.2"
  gem "factory_bot_rails", "~> 6.2"
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "shoulda-matchers", "~> 5.3"
end
