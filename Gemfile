source :rubygems

gem 'rack', '1.2.1'                       # FIXME ~> 1.2.2
gem 'rails', '3.0.1', :require => nil     # FIXME ~> 3.0.6, drop ':require => nil'
gem 'json', '~> 1.5.1'
gem 'plucky', '0.3.6'                     # TODO ~> 0.3.7
gem 'chronic', '~> 0.3.0'
gem 'pony', '~> 1.1'  # unusual version number
gem 'declarative_authorization', :git => "http://github.com/cipherpunk/declarative_authorization.git"
gem 'mongoid', '2.0.0.rc.6'               # TODO 2.0.1
gem 'bson_ext', "~> 1.3.0"

group :development, :test do
  gem 'machinist_mongo', '~> 1.2.0', :require => 'machinist/mongoid'
  gem 'ci_reporter'
  gem 'shoulda', '~> 2.11.3'
  gem 'mocha', '~> 0.9.12'
  gem 'database_cleaner', '~> 0.6.0'
  gem 'faker', '~> 0.3.1'   # TODO ~> 0.9.5
end
