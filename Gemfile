# frozen_string_literal: true

source 'https://rubygems.org/'

group :development, :test do
  gem 'json'
  gem 'metadata-json-lint'
  gem 'puppet-blacksmith'
  gem 'puppet-lint'
  gem 'puppetlabs_spec_helper'
  gem 'rake'
  gem 'rspec-puppet'
  gem 'rubocop'
end

if puppet_version = ENV['PUPPET_VERSION']
  gem 'puppet', puppet_version
else
  gem 'puppet'
end
