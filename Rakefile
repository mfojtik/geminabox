require "rubygems"
require "rubygems/package_task"

task :default => :package

Gem::PackageTask.new(eval(File.read("geminabox.gemspec"))) do |pkg|
end

desc 'Clear out generated packages'
task :clean => [:clobber_package]
