# frozen_string_literal: true

begin
  require "bundler/setup"
rescue LoadError
  puts "You must `gem install bundler` and `bundle install` to run rake tasks"
end

Bundler::GemHelper.install_tasks

require "github_changelog_generator/task"

GitHubChangelogGenerator::RakeTask.new :changelog do |config|
end