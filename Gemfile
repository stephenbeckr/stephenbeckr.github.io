source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
#
# SRB: run `bundle install` and/or `bundle update` after changing this file
#
# # SRB: comment out, following https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll
#gem "jekyll", "~> 4.2.2"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
#gem "minima", "~> 2.5"

# SRB: note on themes, see https://github.com/jekyll/minima/issues/472
# minima 2.5.1 seems to be acting weird (and that's what ~> 2.5 was installing,
#   at ~/.gem/ruby/3.1.2/gems/minima-2.5.1 )
# Try instead this
# (which says: "Using minima 2.5.1 from https://github.com/jekyll/minima.git (at master@41b9769)"")
gem "minima", github: "jekyll/minima"
# That fixes it! (other version of minima 2.5.1 looks for scss in a different
#  location and wasn't working the same)
# See https://github.com/jekyll/minima/issues/472
# (somewhat fixces it... still won't include CSS)

#gem "jekyll-theme-leap-day"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# #   SRB: see https://pages.github.com/versions/ for latest versions
# gem "github-pages", group: :jekyll_plugins
gem "github-pages", "~> 227", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.7"
