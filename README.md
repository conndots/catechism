Catechism
=========
**!!!Important**
This is a small project forked from [aosabook/500lines](https://github.com/aosabook/500lines). I would like to add more and more features that a test framework should do into this project.  

Catechism is a very small test framework for Ruby.


Prerequisites
-------------

* Ruby 2.0.0
* A Unix environment


Installation
------------

Add this line to your application's Gemfile:

    gem 'catechism'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install catechism


Usage
-----

Create a `trials` directory in the root of your project.

Create files in any path underneath it ending in `_trial.rb`.  Examples can be found in `trials/lib/catechism`.

Then, run your test suite:

    $ catechism


Contributing
------------

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

# TODOs
* Refactor code to be DRY.  
* Add tagging support to the trials cases.   
* Add sharing trials support.
