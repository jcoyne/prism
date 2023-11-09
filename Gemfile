# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "rake"
gem "rake-compiler"
gem "test-unit"
gem "ffi", platform: %i[mri mswin mingw x64_mingw]
group :memcheck do
  gem "ruby_memcheck", platform: %i[mri mswin mingw x64_mingw], git: "https://github.com/Shopify/ruby_memcheck", branch: "suppress-intern"
end
gem "rbs", platform: %i[mri mswin mingw x64_mingw]
