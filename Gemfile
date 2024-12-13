source "https://rubygems.org"

# 指定Ruby版本
ruby "~> 3.1"

# 核心依赖
gem "jekyll", "~> 4.3.4"
gem "jekyll-theme-chirpy", "~> 6.0"

# Jekyll 插件
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-paginate", "~> 1.1"
  gem "jekyll-archives", "~> 2.2"
  gem "jekyll-include-cache", "~> 0.2"
  gem "jemoji", "~> 0.13"
end

# 性能优化相关
gem "sass-embedded", "~> 1.58"
gem "webrick", "~> 1.8"
gem "mini_magick", "~> 4.12"

# 开发环境依赖
group :development do
  gem "html-proofer", "~> 5.0"
end

# 通用依赖
gem "tzinfo", "~> 2.0"
gem "tzinfo-data"
gem "wdm", "~> 0.1.1" if Gem.win_platform?
