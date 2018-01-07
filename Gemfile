# frozen_string_literal: true

source 'https://rubygems.org/'

default_puppet_version = '4.10.9'
puppet_version         = ENV.fetch('PUPPET_VERSION', default_puppet_version)

gem 'puppet', puppet_version

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
