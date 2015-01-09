require 'bundler/setup'

# dependencies
require 'json'
require 'rspec/core/rake_task'
require 'uglifier'

# helper module
require File.expand_path('./tasks/support/gl-matrix', File.dirname(__FILE__))
include GLMatrix

Dir[base_path.join './tasks/**/*.rake'].each do |f|
  load f
end
