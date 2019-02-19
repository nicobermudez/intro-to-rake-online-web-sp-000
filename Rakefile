desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

namespace :db do
 
  ...
 
  desc 'seed the database with some dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end
end
