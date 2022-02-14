source 'https://rubygems.org'

git_source(:github) do |repo_name|
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '6.1.4.6'
gem 'mysql2'
gem 'puma', '>= 5.6.2'

gem 'thredded', github: 'sudara/thredded'

# ruby
gem 'sometimes'
gem 'awesome_print', require: 'ap'

# uploading
gem 'http-2' # used by AWS SDK but not in dependencies
gem 'aws-sdk-cloudfront'
gem 'aws-sdk-s3'
gem 'image_processing'
gem 'mime-types'
gem 'ruby-audio'
gem 'ruby-mp3info', require: 'mp3info'
gem 'rubyzip'
gem 's3_direct_upload', '>= 0.1.7'

# active record
gem 'acts_as_list'
gem 'authlogic', github: 'sudara/authlogic', branch: 'rails6-1'
gem 'scrypt' # for authlogic
gem 'request_store' # for authlogic

# view
gem 'nokogiri'
gem 'commonmarker'
gem 'country_select'
gem 'dynamic_form'
gem 'local_time'
gem 'pagy'

# external services
gem 'rakismet'
gem 'postmark-rails', '>= 0.21.0'

# frontend
gem 'webpacker', '>= 5.4.0'
gem 'sass-rails', '>= 6.0.0'
gem 'yui-compressor'
gem 'turbolinks'

# monitoring & perf
gem 'bugsnag'
gem 'oas_agent', github: 'wjessop/oas_agent'
gem 'newrelic_rpm'
gem 'skylight', '~>5.0.0.beta'
gem 'sidekiq'
gem 'dalli'

group :development do
  gem 'perf_check', require: false
  gem 'annotate', require: false
  gem 'faker', require: false
  # Available "channels" of rubocop for code climate:
  # https://github.com/codeclimate/codeclimate-rubocop/branches/all?utf8=✓&query=channel%2Frubocop
  gem 'rubocop', '1.4.1', require: false # synced to .codeclimate.yml
end

## Who loves tests! You do? You do!
group :test do
  gem 'capybara'
  gem 'webdrivers'
  gem 'guard', require: false
  gem 'guard-rspec', require: false
  gem 'listen', require: false
  gem 'percy-capybara'
  gem 'rails-controller-testing', '>= 1.0.5'
  gem 'rb-fsevent', require: false
  gem 'rspec', require: false
  gem 'rspec-core', require: false
  gem 'rspec-expectations', require: false
  gem 'rspec-mocks', require: false
  gem 'rspec-support', require: false
  gem 'rspec-rails', '>= 5.0.1', require: false
  gem 'selenium-webdriver'
  gem 'webmock', require: false
end

group :development, :test do
  gem 'pry'
  gem 'pry-byebug'
end
