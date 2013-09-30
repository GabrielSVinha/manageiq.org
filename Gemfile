# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "~>3.1.5"

# Live-reloading plugin
gem "middleman-livereload"

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end

# For faster file watcher updates for people using Windows
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]


#####
# General plugins

# Blog plugin
gem "middleman-blog"

# favicon support (favicon PNG should be 144×144)
gem "middleman-favicon-maker"

# HTML & XML parsing smarts
gem "nokogiri"

# Syntax highlighting
gem "middleman-syntax"

# For feed.xml.builder
gem "builder", "~> 3.0"


#####
# Bootstrap

# Bootstrap, as SASS 3 version (from master branch, until official release):
gem "bootstrap-sass", github: "thomas-mcdonald/bootstrap-sass"

# Bootstrap 3 version (from a fork; temporary also):
gem "bootstrap-navbar", github: "delynn/bootstrap-navbar"
# Bootstrap-navbar integration for Middleman
gem "middleman-bootstrap-navbar"


#####
# Formats

# less (css)
gem "therubyracer"
gem "less"

# asciidoctor
gem "asciidoctor"

# mediawiki
gem "wikicloth"

# Markdown, with GitHub flavoring
gem "redcarpet"