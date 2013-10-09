source 'https://rubygems.org'
ruby '1.9.3'
gem 'rails', '3.2.14'
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end
gem 'jquery-rails'
gem 'bootstrap-sass', '~> 2.3.2.2'
gem 'cancan'
gem 'devise'
gem 'figaro'
gem 'gibbon'
gem 'rolify'
gem 'simple_form'
group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :mri_20, :rbx]
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'rails_layout'
end
group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'sqlite3'
end
group :production do
  gem 'thin'
  gem 'pg'
end
group :test do
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'cucumber-rails', :require=>false
  gem 'database_cleaner', '1.0.1'
  gem 'email_spec'
  gem 'launchy'
end
