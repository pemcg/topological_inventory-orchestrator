source 'https://rubygems.org'

plugin "bundler-inject", "~> 1.1"
require File.join(Bundler::Plugin.index.load_paths("bundler-inject")[0], "bundler-inject") rescue nil

gem "cloudwatchlogger", "~>0.2"
gem "kubeclient", "~>4.0"
gem "manageiq-loggers", "~>0.4"
gem "more_core_extensions", "~>3.7.0"
gem "optimist"
gem "prometheus_exporter", "~> 0.4.5"
gem "rest-client", "~>2.0"

group :test do
  gem "rake", "~> 10.0"
  gem "rspec", "~> 3.8"
end
