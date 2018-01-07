# frozen_string_literal: true

source 'https://rubygems.org/'

puppetversion = ENV.fetch('PUPPET_GEM_VERSION', '5.3.3')
gem 'puppet', puppetversion

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
