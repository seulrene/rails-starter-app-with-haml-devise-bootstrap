# Rails Starter App

**Don't Repeat Yourself** is the main reason I make this repo!

This is my customized rails starter app(Ruby 2.4, Rails 5.1+) with these changed default settings:

- move `gem 'sqlite3'` to `group :development :test`
- add `gem 'pg'` to `group :production`
- add `gem 'haml-rails'` (use haml as default template engine rather than erb, since haml makes html file smaller and make you more productive)
- add `gem 'devise'` (use devise as authentication system)
- add `gem 'twitter-bootstrap-rails'` (use bootstrap as default website theme)
- add `gem 'jquery-rails'` (Rails 5.1+ needs this gem if using bootstrap)
- add `gem 'devise-bootstrap-views'` (make devise also in bootstrap theme)