task default: :dist

task dist: [:feed]

task :feed do
  File.rename('feed/index.html', 'feed/index.xml')
end
