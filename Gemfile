source "https://rubygems.org"

# Jekyll et ses plugins
gem "jekyll", "~> 4.2.0"
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.7"
end

# Bibliothèques standards pour Ruby 3.4.x
gem 'csv'
gem 'logger'
gem 'base64'
gem 'bigdecimal'
gem 'date'
gem 'fileutils'
gem 'stringio'
gem 'time'

# Plateforme-spécifique
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]