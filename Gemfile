source "https://rubygems.org"

# GitHub Pages gem (includes Jekyll and allowed plugins)
gem "github-pages", "~> 228", group: :jekyll_plugins

# Additional gems for local development
gem "webrick", "~> 1.7"

# Faraday retry gem for Faraday v2.0+
gem "faraday-retry"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]