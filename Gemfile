source 'https://rubygems.org'

ruby '2.2.0'

gem 'rails', '4.2.1'
gem 'pg'

gem 'dotenv-rails'

gem 'slim-rails', '~> 3.0.1'

gem 'sass-rails', '~> 5.0.1'
gem 'bootstrap-sass', '~> 3.3.3'
gem 'momentjs-rails'
gem 'bootstrap3-datetimepicker-rails'

gem 'jquery-rails'
gem 'coffee-rails'

gem 'sorcery'

gem 'rqrcode_png'

gem 'faker'

gem "unicorn-rails"

gem 'twilio-ruby'

gem 'carrierwave'
gem 'fog'

group :production do
  gem 'sendgrid-rails', '~> 2.0'
  gem 'rails_12factor'
end

group :development do
  gem 'spring'
  gem 'letter_opener'
end

group :development, :test do
  gem 'pry-rails'
  gem 'byebug'
  gem 'rspec-rails', '~> 3.1.0'
  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'database_cleaner', '~> 1.4.0'
  gem 'shoulda-matchers', '~> 2.7.0'
end

group :test do
  gem 'codeclimate-test-reporter', require: nil
end

group :assets do
  gem 'therubyracer'
  gem 'uglifier'
end
