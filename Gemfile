if RUBY_PLATFORM == 'java'
  ruby '2.5.0', :engine => 'jruby', :engine_version => '9.2.0' if RUBY_PLATFORM == 'java'
  gem 'gollum-rjgit_adapter', :git => 'https://github.com/repotag/gollum-lib_rjgit_adapter' # For development purposes
  gem 'warbler'
else
  gem 'gollum-rugged_adapter', :git => 'https://github.com/gollum/rugged_adapter.git' # For development purposes
end

gem 'gollum-lib', :git => 'https://github.com/gollum/gollum-lib.git', :branch => 'gollum-lib-5.x' # For development purposes

gemspec
gem 'rake', '~> 11.2'
