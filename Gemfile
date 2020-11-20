source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.2"

gem "pg", ">= 0.18", "< 2.0"

gem "rails", "~> 6.0.3", ">= 6.0.3.4"

# assets
gem "autoprefixer-rails"
gem "aws-sdk-s3"
gem "foundation-icons-sass-rails"
gem "foundation-rails"
gem "image_processing"
gem "jbuilder", "~> 2.7"
gem "premailer-rails"
gem "sass-rails", ">= 6"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 2.7.2"
gem "webpacker", "~> 4.0"

# views
gem "active_link_to"
gem "inky-rb", require: "inky"
gem "meta-tags"
gem "simple_form"
gem "slim"

# all other gems
gem "bootsnap", ">= 1.4.2", require: false
gem "decent_decoration"
gem "decent_exposure"
gem "devise"
gem "draper"
gem "interactor"
gem "kaminari"
gem "puma", "~> 4.1"
gem "pundit"
gem "responders"
gem "secure_headers"
gem "seedbank"
gem "shrine"

group :development, :test do
  gem "brakeman", require: false
  gem "byebug", platforms: %i[mri mingw x64_mingw]
  gem "factory_bot_rails"
  gem "faker"
  gem "rspec-rails"
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "scss_lint", require: false
  gem "slim_lint", require: false
end

group :development do
  gem "letter_opener"
  gem "listen", "~> 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "capybara-email"
  gem "selenium-webdriver"
  gem "slim-rails"
  gem "webdrivers"
end
