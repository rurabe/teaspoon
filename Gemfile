source "https://rubygems.org"

gem "rails", "5.0.0.1"
gem "sprockets", ">= 4.0.0.beta2"

gemspec name: "teaspoon"

group :development, :test do
  gemspec name: "teaspoon-devkit"

  # frameworks
  gem "teaspoon-jasmine", path: "teaspoon-jasmine"
  gem "teaspoon-mocha", path: "teaspoon-mocha"
  gem "teaspoon-qunit", path: "teaspoon-qunit"

  # gems that teaspoon can utilize
  gem "selenium-webdriver", "~> 3.3.0"
  gem "webdrivers", "~> 2.3"
  gem "capybara-webkit"

  # io services
  gem "simplecov", require: false
  gem "codeclimate-test-reporter", "~> 1.0.0", group: :test, require: false
  gem "rubocop", require: false
end
