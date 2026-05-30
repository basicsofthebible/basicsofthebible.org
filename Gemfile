source "https://rubygems.org"

# GitHub Pages supplies/pins the compatible Jekyll version and many core plugins.
gem "github-pages", group: :jekyll_plugins

# Local Hydejack theme included in this repository.
gem "jekyll-theme-hydejack", path: "./#jekyll-theme-hydejack"

# Used to compile math formulas to KaTeX during site building.
gem "kramdown-math-katex"

# JavaScript runtime for Ruby, used by the KaTeX gem above.
gem "duktape"

# Required for `jekyll serve` in Ruby 3.
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-default-layout"
  gem "jekyll-feed"
  gem "jekyll-optional-front-matter"
  gem "jekyll-paginate"
  gem "jekyll-readme-index"
  gem "jekyll-redirect-from"
  gem "jekyll-relative-links"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-titles-from-headings"
  gem "jekyll-include-cache"
  gem "jekyll-avatar"

  # Non-GitHub Pages plugins.
  # These are okay because the site is being built with GitHub Actions.
  gem "jekyll-last-modified-at"
  gem "jekyll-compose"
end

gem "wdm" if Gem.win_platform?
gem "tzinfo-data" if Gem.win_platform?
