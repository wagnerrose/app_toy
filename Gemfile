source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.1'# Use sqlite3 as the database for Active Record
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '5.0.1'
gem 'jbuilder', '2.4.1'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'sqlite3', '1.3.12'
end

group :development do
  gem 'web-console', '3.1.1'
  gem 'listen', '3.0.8'
  gem 'spring', '1.7.2'
  gem 'spring-watcher-listen', '2.0.0'
end

group :production do
  gem 'pg', '0.18.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
