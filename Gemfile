source "https://rubygems.org"

# GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.7"
  gem "jekyll-include-cache"  # Requis pour Minimal Mistakes
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
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