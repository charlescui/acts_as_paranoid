source "http://rubygems.org"

gem "activerecord", "~>4.0"

# Development dependencies
gem "rake"
gem "activesupport", "~>4.0"

platforms :ruby do
  gem "sqlite3"
end

platforms :jruby do
  gem "activerecord-jdbcsqlite3-adapter"
end

group :test do
  gem "autotest-growl"
end
