source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 6.0.0'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'rack-cors'
gem 'active_model_serializers'
gem 'devise_token_auth'
gem 'pundit', '~> 1.1'
gem 'stripe-rails'
gem 'aws-sdk-s3'
gem 'mini_magick'

group :development, :test do
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'factory_bot_rails'
  gem 'coveralls', require: false
  gem 'pundit-matchers', '~> 1.6.0'
  gem 'faker'
  gem 'stripe-ruby-mock', '~> 2.5', require: 'stripe_mock'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end