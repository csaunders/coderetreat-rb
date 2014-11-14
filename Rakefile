$: << File.join(File.dirname(__FILE__), 'lib')
$: << File.join(File.dirname(__FILE__), 'spec')
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec) do |t|
  t.pattern = 'spec/**/*_spec.rb'
end
