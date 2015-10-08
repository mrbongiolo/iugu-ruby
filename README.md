# Iugu Ruby [![Code Climate](https://codeclimate.com/github/jnettome/iugu-ruby/badges/gpa.svg)](https://codeclimate.com/github/jnettome/iugu-ruby) [![Build Status](https://travis-ci.org/jnettome/iugu-ruby.svg)](https://travis-ci.org/jnettome/iugu-ruby)

Ruby gem that provides access to [Iugu - Brazilian Payment Gateway](https://iugu.com)

## Documentation

[API Docs](https://iugu.com/referencias/api)

[Usage samples](https://github.com/jnettome/iugu-ruby/tree/master/doc)

## Installation

Using bundler, add the iugu gem to your gemfile

    gem 'iugu', github: 'jnettome/iugu-ruby'

Or to simply use the iugu ruby binders, fetch on rubygems like

    gem install iugu


### Requirements

  - Ruby 1.9.2 or above

### Development

To run all tests

    bundle exec rake

To run a single test

    bundle exec ruby test/lib/iugu/customer_test.rb
