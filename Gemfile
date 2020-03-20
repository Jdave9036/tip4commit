source 'https://rubygems.org'

ruby '2.4.2'

gem 'rails', '5.2.4.2'

gem 'acts_as_paranoid', github: 'ActsAsParanoid/acts_as_paranoid'
gem 'airbrake', '~> 3.1.15'
gem 'bootstrap_form', github: 'bootstrap-ruby/rails-bootstrap-forms'
gem 'cancancan'
gem 'coffee-rails', '~> 4.2.2'
gem 'demoji'
gem 'devise', '~> 4.4.2'
gem 'devise-i18n'
gem 'dusen', '~> 0.6.1'
gem 'easy_gravatar'
gem 'haml-rails', '~> 0.5.3'
gem 'http_accept_language'
gem 'i18n-js'
gem 'jbuilder', '~> 1.5.3'
gem 'jquery-rails', '~> 4.0', '>= 4.0.1'
gem 'jquery-turbolinks', '>= 2.0.1'
gem 'kaminari', '~> 0.15.0'
gem 'kaminari-i18n', '>= 0.2.0'
gem 'less-rails', '~> 2.4.2'
gem 'money-tree', '~> 0.9.0'
gem 'mysql2', group: :production
gem 'octokit', '~> 4.7.0'
gem 'omniauth', '~> 1.7.1'
gem 'omniauth-github', github: 'alexandrz/omniauth-github', branch: 'provide_emails'
gem 'rails-i18n', '~> 5.0.0'
gem 'render_csv', '>= 2.0.0'
gem 'rest-client'
gem 'sass-rails', '~> 5.0.5'
gem 'sawyer', '~> 0.8.0'
gem 'sdoc', '>= 1.0.0', group: :doc, require: false
gem 'sidekiq'
gem 'therubyracer', '~> 0.12.2', platforms: :ruby
gem 'turbolinks', '~> 2.5.3'
gem 'twitter-bootstrap-rails',    github: 'seyhunak/twitter-bootstrap-rails', branch: 'bootstrap3'
gem 'twitter_bootstrap_form_for', github: 'stouset/twitter_bootstrap_form_for'
gem 'uglifier', '>= 2.4.0'

group :development do
  gem 'capistrano',         '~> 3.4.0'
  gem 'capistrano-bundler', '~> 1.1.2'
  gem 'capistrano-rails',   '~> 1.1.0'
  gem 'capistrano-rvm',     '~> 0.1.0'

  # add ed25519 support to net-ssh
  gem 'bcrypt_pbkdf',       '~> 1.0.0'
  gem 'rbnacl',             '~> 3.4.0'
  gem 'rbnacl-libsodium',   '~> 1.0.0'
end

group :development, :test do
  gem 'factory_girl_rails', '~> 4.3.0'
  gem 'rspec-rails', '~> 3.5.2'
  gem 'sqlite3',            '~> 1.3.11'
end

group :test do
  gem 'cucumber-rails', '>= 1.4.3', require: false
  gem 'database_cleaner'
  gem 'rspec-activemodel-mocks'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'simplecov', '>= 0.15.1'
  gem 'webmock'
  gem 'vcr'
end
