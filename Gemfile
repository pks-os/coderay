source "http://rubygems.org"

# Specify your gem's dependencies in coderay.gemspec
gemspec

# Add dependencies to develop your gem here.
# Include everything needed to run rake, tests, features, etc.
group :development do
  gem "bundler", "~> 1.0.0"
  gem "rake", "~> 0.9.2"
  gem "RedCloth"
  gem "shoulda-context", "= 1.0.0.beta1" if RUBY_VERSION >= '1.8.7'
  gem "json" unless RUBY_VERSION >= '1.9.1'
  gem "rdoc" if RUBY_VERSION >= '1.8.7'
end
