source "https://rubygems.org"

group :development do

  gem "bundler"
  gem "jeweler"


  gem "debugger", :platform => :ruby_19
  gem "byebug", :platform => [:ruby_20, :ruby_21, :ruby_22] & Bundler::Dsl::VALID_PLATFORMS

  gem "rspec", ">= 3"
  gem "nokogiri" # used to test html output

  gem "sqlite3"

  group :mongo do
    gem "mongoid", "3.1.6"
    gem "mongo_mapper", ">=0.11.0"
    gem "bson", "1.4.0"
    gem "bson_ext", "1.4.0"
  end

end
