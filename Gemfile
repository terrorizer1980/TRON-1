# frozen_string_literal: true
source "https://rubygems.org"

gem "fastlane", ">= 2.156.0"
gem 'octokit', '>= 4.19.0'
gem 'netrc'
gem 'jazzy', '0.13.2'
gem 'cocoapods', '>= 1.11.0'
gem 'mime-types'
gem 'cocoapods-trunk'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
