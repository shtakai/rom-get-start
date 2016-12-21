source 'https://rubygems.org'
ruby "2.3.3"

gem 'faker'
gem 'whirly'
gem 'dotenv'
gem 'rom-repository'
gem 'rom-sql'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'thin'
  gem 'paint' # makes whirly colorful
# Use sqlite3 as the database for Active Record
  gem 'sqlite3'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'awesome_print'
  gem "interactive_editor"
end

group :production do
  gem 'pg'
end
