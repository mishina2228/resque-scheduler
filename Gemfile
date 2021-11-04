# vim:fileencoding=utf-8
source 'https://rubygems.org'

case req = ENV['RESQUE']
when nil
  nil # Use the version specified in resque-scheduler.gemspec
when 'master'
  gem 'resque', git: 'https://github.com/resque/resque'
else
  gem 'resque', req
end

gemspec
