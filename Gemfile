source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.3'

gem 'activeadmin', '~> 2.9.0'


group :default, :sidekiq_swarm do
  gem 'rails', '6.1.3.2'

  gem 'aasm', '~> 5.1.1'

  gem 'activerecord-import', '~> 1.0.8', require: false

  gem 'activerecord_json_validator', '~> 1.3.0'

  gem 'aws-sdk', '~> 2.9.37'

  gem 'axlsx', '~> 3.0.0.pre'

  gem 'blazer', '~> 2.4.1'

  gem 'bootsnap', '~> 1.4.5', require: false # required in config/boot.rb

  gem 'braze_ruby', '~> 0.4.2'

  gem 'carrierwave', '~> 1.3.2'

  gem 'coffee-rails', '~> 5.0.0'

  gem 'config', '~> 2.2.3'

  gem 'ddtrace', '~> 0.49', require: false

  gem 'devise', '~> 4.7.1'

  gem 'diffy', '~> 3.2.1'

  gem 'fog-aws', '~> 1.3.0'

  gem 'gender_detector', '~> 1.0.0'

  gem 'geocoder', '~> 1.6.6'

  gem 'gibbon', '~> 3.0.2'

  gem 'gmaps4rails', '~> 2.1.2'

  gem 'google_drive', '~> 3.0.7'

  gem 'google-api-client', '~> 0.50.0', require: %w[google/apis/indexing_v3]

  gem 'google-cloud-talent', '~> 1.0.0', require: %w[google/cloud/talent google/cloud/talent/v4]

  gem 'grape', '~> 1.5.0'
  gem 'grape-entity', '~> 0.8.2'
  gem 'grape-swagger', '~> 1.3.1'
  gem 'grape-swagger-entity', '~> 0.3'
  gem 'grape_logging', '1.8.4'

  gem 'httparty', '0.16.3'

  gem 'iso-639', '~> 0.2.8'

  gem 'jquery-rails', '~> 4.4.0'
  gem 'jquery-ui-rails', '~> 6.0.1'
  gem 'json', '~> 2.5.1'
  gem 'json-schema', '~> 2.8.1'
  gem 'jwt', '~> 2.1.0'

  gem 'kaminari', '~> 1.2.1'
  gem 'kraken-io', '~> 0.1.3'

  gem 'letter_avatar', '~> 0.3.7'
  gem 'lograge', '~> 0.10.0'
  gem 'lograge-sql', '~> 1.3.1'

  gem 'mail', '~> 2.7.1'
  gem 'mini_magick', '~> 4.11.0'

  gem 'nilify_blanks', '~> 1.3.0'
  gem 'nokogiri', '~> 1.11.4'

  gem 'paranoia', '~> 2.4.3'

  gem 'pdf-reader', '~> 2.0.0'
  gem 'pdfkit', '~> 0.8.2'

  gem 'pg', '~> 1.2.3'

  gem 'pg_query', '~> 1.3.0'

  gem 'pg_search', '~> 2.1.2'

  gem 'pghero', '~> 2.7'

  gem 'prawn-table', '~> 0.2.2'
  gem 'public_suffix', '~> 3.0.3'
  gem 'puma', '~> 5.3.1'
  gem 'pundit', '~> 1.1.0'

  gem 'rack', '~> 2.2.3'
  gem 'rack-attack', '~> 6.4'
  gem 'rack-cors', '~> 1.1.1'
  gem 'rails-jquery-autocomplete', '~> 1.0.4'
  gem 'redis', '~> 4.2.5'
  gem 'rest-client', '~> 2.0.2'
  gem 'roo', '~> 2.7'

  gem 'sass-rails', '~> 5.0.7'
  gem 'react-rails', '~> 2.6.1' # react-rails needs to be after sass-rails
  gem 'inherited_resources', '~> 1.9' # inherited_resources need to be loaded before paper trail and after sass-rails

  gem 'paper_trail', '~> 11.1.0'
  gem 'sdoc', '~> 2.0.3', group: :doc
  gem 'scenic', '~> 1.5.4'
  gem 'slack-notifier', '~> 2.2.1'
  gem 'slim', '~> 3.0.8'
  gem 'sprockets', '~> 3.7.2'

  gem 'strong_migrations', '~> 0.7.8'

  gem 'money-rails', '~> 1.13.4' # money-rails needs to be loaded after strong migrations
  gem 'uglifier', '~> 4.0.1'
  gem 'webpacker', '~> 5.2.1'
  gem 'whenever', '~> 1.0.0'

  gem 'x-editable-rails', '~> 1.5.5'
  gem 'zip-zip', '~> 0.3'
  gem 'maxminddb', '~> 0.1.22'
  gem 'active_admin_theme', '~> 1.0.3'

  gem 'sentry-ruby', '~> 4.3.1'
  gem 'sentry-rails', '~> 4.3.3'
  gem 'sentry-sidekiq', '~> 4.3.0'

  gem 'sidekiq', '~> 6.1.3' # parent for sentry-sidekiq

  gem 'tzinfo-data' # do no set version for tzinfo-data

  gem 'hashdiff', '~> 1.0.0'

  gem 'dotiw', '~> 4.0'

  # hairtrigger causing the problem to overwrite primary schema.rb file
  gem 'hairtrigger', '~> 0.2.24'
end

# Use postgresql as the database for Active Record
#gem 'pg', '~> 1.1'
# Use Puma as the app server
#gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
#gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
#gem 'webpacker', '~> 5.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
# gem 'bootsnap', '>= 1.4.4', require: false ---> TODO to check both uses

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
