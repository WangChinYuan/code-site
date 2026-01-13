source "https://rubygems.org"

gem "jekyll", "~> 4.4.1"

# 主題
gem "just-the-docs"

# 插件群組 (根據 CSDN 文章建議擴充)
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-remote-theme"
  gem "jekyll-seo-tag" # 用於 SEO 優化
  gem "jekyll-sitemap" # 生成站點地圖
end

# Windows 支援
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]