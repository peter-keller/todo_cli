require 'sinatra/activerecord/rake'
require_relative "config/environment"

desc 'Start our app console'
task :console do
    Pry.start
end

desc 'Run the app'
task :run do
  cli = CLI.new
  cli.start
end