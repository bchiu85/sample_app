source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.2'
# Use sqlite3 as the database for Active Recordgem 'sqlite3'
gem 'pg'

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'rspec-rails'
end

  group :test do
  	gem 'rspec'
end
