source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.6'

gem 'rails', '~> 6.0.5'
gem 'sqlite3', '~> 1.4'
gem 'puma', '~> 4.1'
gem 'bootsnap', '>= 1.4.2', require: false

#Devise
gem 'devise'
gem 'devise_token_auth'

#HTTP通信
gem 'rack-cors'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Railsプロジェクトでenvファイルを使用する
  gem 'dotenv-rails'
end

group :development do
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
