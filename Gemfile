source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins

source "https://rubygems.pkg.github.com/scamartists" do
  gem "scammed-theme"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
