namespace :site do
  desc 'Clean - remove generated files'
  task :clean do
    system "rm -rf _site"
  end

  desc 'Build and run for development'
  task :dev do
    system "jekyll --server --auto"
  end

  task :gen do
    system "jekyll"
  end
end
