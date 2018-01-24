source 'https://rubygems.org'

gemspec

gem 'stackprof', platforms: :mri

group :benchmark, :test do
  gem 'benchmark-ips'
end

group :test do
  gem 'rubocop', '~> 0.49.0'

  platform :mri do
    gem 'liquid-c', github: 'Shopify/liquid-c', branch: 'fix-rtrim-followed-by-tag'
  end
end
