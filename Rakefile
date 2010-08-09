require 'rubygems'  
require 'rake'  
  
begin  
  require 'jeweler'  
  Jeweler::Tasks.new do |gemspec|  
    gemspec.name = "nginx_config_generator_kthompson"  
    gemspec.summary = "Creates Nginx config files from YAML options"
    gemspec.description = "You got Nginx in my YAML! You got YAML in my Nginx!"
    gemspec.email = "mrunleaded@gmail.com"
    gemspec.homepage = "http://github.com/kthompson/nginx_config_generator"
    gemspec.authors = ["Kevin Thompson", "Chris Wanstrath"]
    gemspec.executables = ["generate_nginx_config"]
  end  
rescue LoadError  
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"  
end  
  
Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }