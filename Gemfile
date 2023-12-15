source "https://rubygems.org"

ruby "3.2.2"

gem "rails", "~> 7.1.1"

gem "bcrypt"
gem "faker"
gem "will_paginate",           "3.3.1"
gem "bootstrap-will_paginate"
gem "bootstrap-sass"
gem "sprockets-rails"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails" 
gem "jbuilder"   
gem "puma"   
gem "bootsnap", require: false
gem "sqlite3"
gem "active_storage_validations"
gem "image_processing"

group :production do
  gem "pg"
end

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  gem "web-console"
  gem "solargraph"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "rails-controller-testing"
  gem "minitest"
  gem "minitest-reporters"
  gem "guard"
  gem "guard-minitest"
end