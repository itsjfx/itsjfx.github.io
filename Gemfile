source "https://rubygems.org"

# Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#

# Happy Jekylling!
gem "jekyll", "~> 4.2.0"

# This is the default theme for new Jekyll sites.
gem "minima", github: "jekyll/minima"

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15.1"
  gem "jekyll-sitemap", "~> 1.4.0"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
