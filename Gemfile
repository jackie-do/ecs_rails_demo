source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

## CORE GEMS
gem "rails", "~> 7.0.4"
gem "sprockets-rails"
gem "mysql2", "~> 0.5" # Use mysql as the database for Active Record
gem "puma", "~> 5.0" # Use the Puma web server [https://github.com/puma/puma]
gem "importmap-rails" #Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "turbo-rails" # Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "stimulus-rails" # Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "jbuilder" # Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "redis", "~> 4.0" # Use Redis adapter to run Action Cable in production

## ADDTIONAL GEMS
gem "bootsnap", require: false # Reduces boot times through caching; required in config/boot.rb
gem "sidekiq"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console" # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "rack-mini-profiler" # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
