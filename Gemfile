# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"
group :jekyll_plugins do
  # ashmaroli
  gem "jekyll-data", "~> 1.1.1"
  # wikibonsai
  gem "jekyll-semtree", "~> 0.0.3"
  gem "jekyll-wikirefs", "~> 0.0.14"
end

gem "webrick", "~> 1.7"
