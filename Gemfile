source 'http://rubygems.org'

gem 'nokogiri', '1.8.5'

allow_local = true

if allow_local && File.exist?('../openstudio-extension-gem')
  # gem 'openstudio-extension', github: 'NREL/openstudio-extension-gem', branch: 'develop'
  gem 'openstudio-extension', path: '../openstudio-extension-gem'
else
  #gem 'openstudio-extension', github: 'NREL/openstudio-extension-gem', branch: 'develop'
  gem 'openstudio-extension', github: 'NREL/openstudio-extension-gem', branch: 'develop'
end

# simplecov has an unneccesary dependency on native json gem, use fork that does not require this
gem 'simplecov', github: 'NREL/simplecov'
