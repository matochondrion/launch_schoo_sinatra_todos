desc "Start a local server accessible at the server's IP address"
task :start_local_server do
  sh 'bundle exec ruby todo.rb -o 0.0.0.0'
end

desc "Default task(s)"
task default: :start_local_server

