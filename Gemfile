# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "jekyll", ">= 3.7", "< 5.0"

gem "github-pages", group: :jekyll_plugins

gem "tzinfo-data"
gem "wdm", "~> 0.1.0" if Gem.win_platform?

gem 'rake', :group => :development

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-paginate", "~> 1.1"
  gem "jekyll-sitemap", "~> 1.3"
  gem "jekyll-gist", "~> 1.5"
  gem "jekyll-feed", "~> 0.1"
  gem "jekyll-include-cache", "~> 0.1"

  gem "jemoji"
  gem "jekyll-algolia"
end
