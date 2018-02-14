# OneNote

This is an Evernote clone.

## Gemfile

```ruby
gem 'devise'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'cancancan'

gem 'wysiwyg-rails'
gem 'toastr-rails'
```

## Installing Gems

```sh
bundle

bundle exec spring binstub --all
````

### Devise

```sh
rails generate devise:install

rails generate devise User

rake db:migrate
```

### CanCanCan

```ruby
rails g cancan:ability
```

### MailCatcher

```ruby
gem install mailcatcher
```

Running MailCatcher:
```sh
mailcatcher --ip=0.0.0.0
```