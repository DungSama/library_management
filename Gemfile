
source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.7'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'simple_form', '~> 3.5'
gem 'bootstrap-sass', '~> 3.3.4.1'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'devise', '~> 4.2', '>= 4.2.1'
gem 'paperclip', '~> 5.1'
gem 'stripe', '~> 3.9'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'whenever', require: false
gem 'will_paginate', '~> 3.1.0'
gem 'sdoc', '~> 0.4.0', group: :doc


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'sqlite3'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem "pg"

end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]