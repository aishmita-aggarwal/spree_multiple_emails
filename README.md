SpreeMultipleEmails
===================

[![Code Climate](https://codeclimate.com/github/vinay-mittal/spree_multiple_emails/badges/gpa.svg)](https://codeclimate.com/github/vinay-mittal/spree_multiple_emails)
[![Issue Count](https://codeclimate.com/github/vinay-mittal/spree_multiple_emails/badges/issue_count.svg)](https://codeclimate.com/github/vinay-mittal/spree_multiple_emails)
[![Test Coverage](https://codeclimate.com/github/vinay-mittal/spree_multiple_emails/badges/coverage.svg)](https://codeclimate.com/github/vinay-mittal/spree_multiple_emails/coverage)

Introduction goes here.

Installation
------------

Add spree_multiple_emails to your Gemfile:

```ruby
gem 'spree_multiple_emails'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_multiple_emails:install
```

Testing
-------

First bundle your dependencies, then run `rake`. `rake` will default to building the dummy app if it does not exist, then it will run specs. The dummy app can be regenerated by using `rake test_app`.

```shell
bundle
bundle exec rake
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_multiple_emails/factories'
```

Copyright (c) 2016 [Vinay Mittal], released under the New BSD License
