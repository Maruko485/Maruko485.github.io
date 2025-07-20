source 'https://rubygems.org'

group :jekyll_plugins do
  gem 'jekyll'
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
  gem 'webrick', '~> 1.8'
end

gem 'github-pages'
gem 'connection_pool', '2.5.0'


#Just a Windows-only timezone fix 
platforms :mingw, :x64_mingw, :mswin do
  gem "tzinfo-data"
  gem "tzinfo", ">= 1", "< 3"   # keeps tzinfo 2.x which JST/EST conversion relies on
end
