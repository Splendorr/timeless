Timeless
========

Timeless is a mixture between a blog, wiki and CMS. For now, have a look at
<http://timeless.judofyr.net/timeless> for description.

To run this locally:

1. Clone the repo with git.
2. Make sure you're running Ruby 1.8.7
3. Use "bundle install" from within the directory to install all the necessary gems.
(3a. If Oniguruma doesn't compile on Mac OS X, I recommended using [Homebrew](https://github.com/mxcl/homebrew) to install it.)
4. Once everything is installed, run
> bundle exec rackup -p 3301