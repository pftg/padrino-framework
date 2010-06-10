source :rubygems

gem "sinatra", ">= 1.0.0"
gem "http_router", ">= 0.2.2"
gem "thor", ">= 0.13.0"

# If you want try our test on AS edge.
# $ rake test AS=edge
if ENV['AS'] == "edge"
  puts "Using ActiveSupport 3.0.0.beta4"
  gem "activesupport", ">= 3.0.0.beta4", :require => 'active_support'
  gem "tzinfo"
else
  puts "Using ActiveSupport 2.3.8"
  gem "activesupport", ">= 2.3.8", :require => 'active_support'
end

gem "shoulda", ">= 2.10.3"
gem "i18n", ">=0.3.7"
gem "mail", ">= 2.2.0"
gem "builder", ">= 2.1.2"

group :db do
  gem "dm-core", ">= 1.0"
  gem "dm-migrations", ">= 1.0"
  gem "dm-validations", ">= 1.0"
  gem "dm-aggregates", ">= 1.0"
  gem "dm-sqlite-adapter", ">= 1.0"
end

gem "rake",  ">= 0.8.7"
gem "mocha", ">= 0.9.8"
gem "rack-test", ">= 0.5.0"
gem "webrat", ">= 0.5.1"
gem "haml", ">= 2.2.22"