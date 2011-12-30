#!/usr/bin/env ruby

require 'rubygems'
require 'bundler/setup'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "rump"
    gemspec.summary = "Rump helps you run Puppet locally against a Git checkout."
    gemspec.description = "Rump helps you run Puppet locally against a Git checkout. This is great for locally iterating your Puppet manifests very quickly, then pushng them up to a repository somewhere else to share the changes."
    gemspec.email = "ops@railsmachine.com"
    gemspec.homepage = "http://github.com/railsmachine/rump"
    gemspec.authors = ["Lindsay Holmwood"]
    gemspec.add_dependency 'thor', '0.13.4'
    gemspec.add_dependency 'bundler', '1.0.10'
  end
rescue LoadError
  puts "Jeweler not available. Install it with: gem install jeweler"
end
