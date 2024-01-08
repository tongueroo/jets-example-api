source "https://rubygems.org"

gem "jets", ">= 5.0"
gem "importmap-jets"
gem "sprockets-jets"
gem "sassc" # only required if using sass in stylesheets

# Include mysql2 gem if you are using ActiveRecord, remove if you are not
gem "mysql2", "~> 0.5.2"

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'shotgun'
  gem 'rack'
  gem "puma"
end

group :test do
  gem 'rspec' # rspec test group only or we get the "irb: warn: can't alias context from irb_context warning" when starting jets console
  gem 'launchy'
  gem 'capybara'
end
