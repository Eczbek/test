require "bundler/setup"
require "jekyll"

desc "Build the site"
task :build do
  Jekyll::Command.build
end

desc "Serve the site"
task :serve do
  Jekyll::Command.build
  Jekyll::Command.serve
end
