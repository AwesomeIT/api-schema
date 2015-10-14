require 'json'
require 'yaml'

# Create JSON from YML
namespace :generate do 
  task :json do 
    File.open('swagger.yaml', 'r') do |yaml|
      File.delete('swagger.json') if File.exist?('swagger.json')

      File.open('swagger.json', 'w+').write(JSON.dump(YAML::load_file('swagger.yaml')))
    end
  end
end