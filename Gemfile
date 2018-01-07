# frozen_string_literal: true

source 'https://rubygems.org/'

group :development, :test do
  gem 'json', :require => false
  gem 'metadata-json-lint', :require => false
  gem 'puppet-blacksmith', :require => false
  gem 'puppet-lint', :require => false
  gem 'puppetlabs_spec_helper', :require => false
  gem 'rake', :require => false
  gem 'rspec-puppet', :require => false
  gem 'rubocop', :require => false
end

if puppet_version = ENV['PUPPET_VERSION']
  gem 'puppet', puppet_version, :require => false
else
  gem 'puppet', :require => false
end
