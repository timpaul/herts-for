source 'https://rubygems.org'

require 'json'
require 'open-uri'

#versions = JSON.parse(open('https://pages.github.com/versions.json').read)
versions = JSON.parse('{"jekyll":"3.3.0","jekyll-sass-converter":"1.3.0","kramdown":"1.11.1","liquid":"3.0.6","rouge":"1.11.1","github-pages-health-check":"1.2.0","jemoji":"0.7.0","jekyll-mentions":"1.2.0","jekyll-redirect-from":"0.11.0","jekyll-sitemap":"0.12.0","jekyll-feed":"0.8.0","jekyll-gist":"1.4.0","jekyll-paginate":"1.1.0","jekyll-coffeescript":"1.0.1","jekyll-seo-tag":"2.1.0","jekyll-github-metadata":"2.2.0","jekyll-avatar":"0.4.2","listen":"3.0.6","activesupport":"4.2.7","minima":"2.0.0","jekyll-swiss":"0.4.0","ruby":"2.3.1","github-pages":"104","html-pipeline":"2.4.2","sass":"3.4.22","safe_yaml":"1.0.4"}')
gem 'github-pages', versions['github-pages']

group :development do
    gem 'foreman'
    gem 'octopress-autoprefixer'
end

group :test do
    gem 'rake', '~> 11.0.0'
    gem 'jekyll', versions['jekyll']
    gem 'html-proofer', '~> 3.0.0'
end
