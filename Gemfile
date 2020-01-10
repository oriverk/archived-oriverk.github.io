source 'https://rubygems.org'

## If you want to host your site on Github Pages Open Gemfile and delete
# gem "jekyll", "~> 3.8.6"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.

gem 'rouge'
gem 'jekyll-autoprefixer'


gem 'github-pages', group: :jekyll_plugins

group :jekyll_plugins do
  gem 'jekyll-admin'
  gem 'jekyll-feed', '~> 0.6'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ /mingw|mswin|java/ } do
  gem 'tzinfo', '~> 1.2'
  gem 'tzinfo-data'
end

# Performance-booster for watching directories on Windows
gem 'wdm', '~> 0.1.0', install_if: Gem.win_platform?

# for scss on jekyll
gem 'jekyll-coffeescript'
