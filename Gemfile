# frozen_string_literal: true

source 'https://rubygems.org'

ruby '2.7.3'

gem 'activeadmin', '~> 2.9.0'

# Some of our gems are not required or doesn't work with sidekiq swarm (like activeadmin)
# so using groups we can exclude them from being loaded by swarm and at the same time
# keep those excluded in default group so they are loaded by other processes like rails

group :default, :sidekiq_swarm do
  gem 'rails', '6.1.3.2'
  # rails needs to be before blazer to avoid issues in sidekiq
  gem 'aasm', '~> 5.1.1'
  gem 'activerecord-import', '~> 1.0.8', require: false
  gem 'activerecord_json_validator', '~> 1.3.0'
  gem 'aws-sdk', '~> 2.9.37'
  gem 'axlsx', '~> 3.0.0.pre'
  gem 'blazer', '~> 2.4.1'
  gem 'bootsnap', '~> 1.4.5', require: false # required in config/boot.rb
  gem 'braze_ruby', '~> 0.4.2'
  gem 'capitalize-names', git: 'https://github.com/heyjobs/capitalize-names'
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
  gem 'mandrill-api', git: 'https://github.com/heyjobs/mandrill-api-ruby', branch: 'main'
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
  gem 'tzinfo-data' # do no set version for tzinfo-data
  gem 'hashdiff', '~> 1.0.0'
  gem 'dotiw', '~> 4.0'
  gem 'hairtrigger', '~> 0.2.24'
  gem 'json-streamer', '~> 2.1.0'
  gem 'sys-filesystem', '~> 1.4.1'
  gem 'sneakers', '~> 2.11.0'
  gem 'restforce', '~> 5.0.5'
  gem 'google-id-token', '~> 1.4.2'
  gem 'json-jwt', '~> 1.13'
  gem 'dry-validation', '~> 1.6'
  gem 'shoryuken', '~> 5.0.6'

  gem 'sidekiq', '~> 6.1.3'

  source 'https://enterprise.contribsys.com/' do
    gem 'sidekiq-ent', '~> 2.2.1'
    gem 'sidekiq-pro', '~> 5.2.1'
  end

  # needs to be required after sidekiq ent
  gem 'attr_encrypted', '~> 3.1.0', git: 'https://github.com/attr-encrypted/attr_encrypted' # https://github.com/attr-encrypted/attr_encrypted/issues/389
  gem 'retriable', '~> 3.1.2'
end

group :staging, :development, :test do
  gem 'fabrication', '~> 2.21'
  gem 'rspec-rails', '~> 5.0.0'
  gem 'faker', '~> 1.9.6'
end

group :development, :test do
  gem 'brakeman', '~> 4.7.2'
  gem 'bullet', '~> 6.1.4'
  gem 'byebug', '~> 11.1.1'
  gem 'capybara', '~> 3.35'
  gem 'dotenv-rails', '~> 2.7.6'
  gem 'parallel_tests', '~> 2.31'
  gem 'pry', '~> 0.13.1'
  gem 'rspec-snapshot', '~> 0.1.2'
  gem 'rspec-sqlimit', '~> 0.0.3'
  gem 'shoulda-matchers', '~> 3.1.3'
  gem 'simplecov', '~> 0.17.1'
  gem 'vcr', '~> 5.0.0'
  gem 'webdrivers', '~> 4.2'
  gem 'webmock', '~> 3.8.1'
end

group :development do
  gem 'awesome_print', '~> 1.8.0'
  gem 'annotate', '~> 3.1.1'
  gem 'better_errors', '~> 2.5'
  gem 'binding_of_caller', '~> 0.8', require: false
  gem 'foreman', '~> 0.87.2', require: false
  gem 'guard-bundler', '~> 3.0', require: false
  gem 'guard-rspec', '~> 4.7.3', require: false
  gem 'hirb', '~> 0.7.3'
  gem 'lefthook', '~> 0.6.3'
  gem 'reek', '~> 6.0.1', require: false
  gem 'rubocop', '~> 0.74.0', require: false
  gem 'rubocop-rails', '~> 2.3.2', require: false
  gem 'rubocop-performance', '~> 1.4.1', require: false
  gem 'rubocop-rspec', '~> 1.35.0', require: false
  gem 'rubocop-rspec-focused', '~> 1.0.0', require: false
  gem 'ruby-prof', '~> 0.17.0', require: false
  gem 'spring', '~> 2.1.1'
  gem 'spring-commands-rspec', '~> 1.0.4'
  gem 'yaml-lint', '~> 0.0.10'
end

group :test do
  gem 'rspec_junit_formatter', '~> 0.4.1'
  gem 'rspec-sidekiq', '~> 3.0.3'
  gem 'rspec-collection_matchers', '~> 1.2'
  gem 'super_diff'
end
