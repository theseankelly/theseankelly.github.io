source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-paginate", "~> 1.1"
  gem "jekyll-sitemap", "~> 1.3"
  gem "jekyll-gist", "~> 1.4"
  gem "jekyll-feed", "~> 0.1"
  gem "jekyll-seo-tag", "~> 2.4"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

