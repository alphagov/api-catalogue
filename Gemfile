# If you do not have OpenSSL installed, change
# the following line to use 'http://'
source "https://rubygems.org"

gem "rake"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", platforms: %i[mswin mingw]

# Windows does not come with time zone data
gem "tzinfo-data", platforms: %i[mswin mingw jruby]

# For data attributes
gem "activemodel"

group :test do
  gem "factory_bot"
  gem "rspec"
end

group :development do
  gem "rubocop-govuk"
end

group :development, :test do
  gem "pry"
end

# From tech-docs-gem - to be revised
gem "activesupport"
gem "middleman", "~> 4.0"
gem "middleman-autoprefixer", "~> 2.10.0"
gem "middleman-compass", ">= 4.0.0"
gem "middleman-livereload"
gem "middleman-search-gds"
gem "middleman-sprockets"
gem "redcarpet", "~> 3.5.0"
gem "sass"
gem "sprockets", "~> 4.0.0"
