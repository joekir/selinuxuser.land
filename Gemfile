# frozen_string_literal: true

source 'https://rubygems.org'

require 'json'
require 'net/http'
versions = JSON.parse(Net::HTTP.get(URI('https://pages.github.com/versions.json')))

# 2nd arg is a ratchet to ensure it's at lea
gem 'github-pages', versions['github-pages']
gem 'jekyll'
gem 'just-the-docs', '>= 0.3.3'
gem 'webrick'
