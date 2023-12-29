require 'jekyll'

task :default => :site

task :site => :jekyll do
  Jekyll::Site.new(site_config).run
end

site_config = {
  'source' => '.',
  'destination' => '_site',
}
