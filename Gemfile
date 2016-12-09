source 'https://rubygems.org'
ruby "2.3.1"


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'


gem 'rollbar'
gem 'lograge'
gem 'sidekiq'
gem 'octokit', :git => 'https://github.com/octokit/octokit.rb.git', :branch => 'bearer-authentication'
gem 'travis'
gem 'omniauth', '~> 1.3'
gem 'omniauth-github', '~> 1.1'
gem 'jwt'

gem 'jekyll', '~> 3.3'

gem 'gems'
gem 'foundation-rails', '~> 6.2'
gem 'font-awesome-rails', '~> 4.6'

gem 'gemnasium-parser'
# gem 'sinatra', :require => nil
gem 'slack-poster'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  # have an .env file for environment variables (to keep secrets out of the code base, for example)
  gem 'dotenv-rails'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'rr', require: false
  gem 'vcr', require: false
  gem 'webmock', require: false
end
