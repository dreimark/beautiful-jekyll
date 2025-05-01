# frozen_string_literal: true

source "https://rubygems.org"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem 'rake', '12.3.3' # Hinzugefügt, um die fehlende Abhängigkeit zu beheben
gem 'appraisal', '2.5.0' # Hinzugefügt, um die fehlende Abhängigkeit zu beheben
gem 'thor', '1.3.2' # Hinzugefügt, um die fehlende Abhängigkeit zu beheben

gemspec

