source 'https://rubygems.org'

gemspec

group :benchmark do
  gem 'activesupport', "#{RUBY_VERSION < '2.2' ? '<' : '>'} 5", require: false

  gem 'benchmark-ips', '~> 2.0', require: false
  gem 'business_time',           require: false
  gem 'working_hours',           require: false
end

group :test do
  gem 'codeclimate-test-reporter', '~> 1.0',    require: false
  gem 'simplecov',                 '~> 0.14.0', require: false
end

group :development, :test do
  gem 'bump',    '~> 0.5.0',  require: false
  gem 'rake',    '~> 12.0',   require: false
  gem 'rspec',   '~> 3.0',    require: false
  gem 'rubocop', '~> 0.48.0', require: false
end
