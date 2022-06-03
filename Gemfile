ruby '2.0.0'

source 'https://rubygems.org'

gem "facter", ">= 1.7.6"
gem 'rake'
gem 'thor'
case RUBY_PLATFORM
when /darwin/
  gem 'CFPropertyList'
end

group :test do
  gem 'rspec', '> 2.13.0'
  gem 'rspec-core', '> 2.13.0'
  gem 'rspec-expectations', '> 2.13.0'
  gem 'rspec-mocks', '> 2.13.0'
  gem 'fakefs',  '~> 0.13.3'
  gem 'simplecov'
  gem 'fuubar'
end
