task(:default) do 
  require_relative 'test' 
end

desc "run the tests"
task :test => :default

desc "run service"
task :server do
  sh "ruby number_cruncher.rb"
end
desc "check it for the fifth Fermat number using curl"
task :fermat5 do
  sh "curl http://localhost:4567/4294967297"
end
