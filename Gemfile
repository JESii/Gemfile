source 'http://rubygems.org'

gem 'rails', '3.0.9'
gem 'jquery-rails'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3', '1.3.3', :require => 'sqlite3'
gem 'simple_form', '~> 1.3.1'
gem 'haml'
gem 'haml-rails'
gem 'dynamic_form', '1.1.4'
gem 'decent_exposure'
gem 'will_paginate', "~> 3.0.pre2"
gem 'pdfkit'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
	gem 'rspec'
	gem 'rspec-rails'
  #Heroku can't find this gem, only tomkersten-annotate-models
  #But bundler can't find this gem on my system...???
  #So we have to run this command to find tom's stuff in the EE libs
  #gem sources -a http://gems.github.com
  # But then we find that hoe required rubygems 1.4 and we have 1.3.7
  # and Debian won't allow gem update --system <psigh>
  #gem 'tomkersten-annotate-models'
  gem 'webrat'
	gem 'hpricot'
	gem 'ruby_parser'
	gem 'factory_girl', '1.3.3'
	gem 'factory_girl_rails', '1.0.1'
	gem 'database_cleaner', '0.6.7'
	gem 'rspec2-rails-views-matchers', '0.0.3'
	#gem 'zachinglis-rspec-haml-scaffold'
	gem 'nifty-generators'
	gem 'cucumber-rails', '0.5.0'
  # To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
  # gem 'ruby-debug'
  gem 'ruby-debug19', :require => 'ruby-debug'

end
