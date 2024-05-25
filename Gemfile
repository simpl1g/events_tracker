source "https://rubygems.org"

# Use main development branch of Rails
gem "rails", github: "rails/rails", branch: "main"
gem "sqlite3", ">= 1.4"
gem "puma"
gem "kamal", require: false
gem "bootsnap", require: false
gem "sprockets-rails"
gem "vite_rails"
gem "litestack", "0.4.4"

group :development, :test do
  gem "brakeman", require: false

  gem "rubocop-rails-omakase", require: false
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
end
