# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'slack-ruby-bot'
gem 'celluloid-io'

gem 'puma'
gem 'sinatra'

group :development, :test do
  gem 'rake', '~> 10.4'
  gem 'rubocop', '0.31.0'
  gem 'foreman'
end

group :test do
  gem 'rspec'
  gem 'rack-test'
  gem 'vcr'
  gem 'webmock'
end