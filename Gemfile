source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

group :test do
  gem 'kramdown'
  gem 'jekyll'
  gem 'html-proofer'
  gem 'rake'
end
