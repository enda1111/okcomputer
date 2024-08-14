source "https://rubygems.org"

RAILS_VERSION = ENV.fetch("RAILS_VERSION", "7.2")

gem "rails", "~> #{RAILS_VERSION}"
if RAILS_VERSION.start_with?("6") || RAILS_VERSION.start_with?("7")
  gem "sqlite3", "~> 1.4"
end

gem 'sprockets', '~>3.0'

gemspec
