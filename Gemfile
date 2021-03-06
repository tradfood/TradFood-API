source 'https://rubygems.org'
ruby '~> 2.3.1'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.4'
# Fix console bug
gem 'rb-readline'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0', '>= 5.0.7'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2', '>= 4.2.2'
# Use rails-admin to administrate the app
gem 'rails_admin', '>= 1.3.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use carrierwave for image management
gem 'carrierwave'
# Use Redcarpet to convert markdown to HTML
gem 'redcarpet'
# Use Rollbar to catch errors
gem 'rollbar'
# Use whenever to add CRON tasks
gem 'whenever'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use rack CORS to enable CORS request
gem 'rack-cors', :require => 'rack/cors'
# Preventing API for abuse
gem 'rack-attack'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  # Use rspec for unit tests
  gem 'rspec-rails', '>= 3.6.0'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.5.1'
  gem 'listen', '~> 3.0.8'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.1'
  # Generate PDF to show the database model
  gem 'rails-erd'
end

group :production do
  # Use pg (postgresql) as the database for Active Record
  gem 'pg'
  # Rails library tuned to run smoothly on Heroku/Dokku cloud infrastructures
  gem 'rails_12factor'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
