namespace :greeting do 
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
  
  task :hola do
    puts "hola de Rake!"
  end
end

namespace :db do
  desc "db migrate"
  task :migrate => :environment do
    
  end
  task :environment do
    require_relative "./config/environment"
  end
  
  task :seed => :environment do
    require_relative "./db/seeds"
  end
end