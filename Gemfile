source 'https://gems.ruby-china.com'

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem "github-pages", group: :jekyll_plugins

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

# gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'hawkins'
end


# 修复 Ruby 3.4.0 移除默认库导致的报错
gem "csv"
gem "logger"
gem "bigdecimal"
# 补充：在较新的 Ruby 版本中运行旧版 Jekyll，通常还需要下面这两个库，建议一并加上防患于未然
gem "webrick", "~> 1.8"
gem "base64"
