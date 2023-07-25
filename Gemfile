source 'https://rubygems.org'

# Use Berkshelf for resolving cookbook dependencies
gem 'berkshelf', '~> 3.0'

# Install omnibus software
gem 'omnibus', :github => 'chef/omnibus', :branch => '7.0.9'
gem 'omnibus-software', :github => 'chef/omnibus-software' #, :branch => 'omnibus/3.2-stable'

# Use open_uri_redirections to allow HTTPS -> HTTP redirections in omnibus
gem 'open_uri_redirections', '0.2.1'

# Use Test Kitchen with Vagrant for convering the build environment
gem 'test-kitchen',    '~> 1.2'
gem 'kitchen-vagrant', '~> 0.14'

group :test do
  gem 'rake', '~> 12.3.3'
  gem 'serverspec', '~> 2.18.0'
end
