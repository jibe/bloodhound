require "rspec/core/rake_task"

begin
  require "mg"
  MG.new("bloodhound.gemspec")

  task :build => :vendor
rescue LoadError
end

desc "Default: run specs"
task :default => :spec
