# frozen_string_literal: true

source "https://rubygems.org"

# Carga el .gemspec del tema (Chirpy usa esto)
gemspec

# Plugins necesarios
gem "jekyll-feed", "~> 0.17"
gem "jekyll-seo-tag"

# Para tests (tu línea original)
gem "html-proofer", "~> 5.0", group: :test

# Soporte para Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
