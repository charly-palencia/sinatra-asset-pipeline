Sinatra with Sprockets 2 (Asset Pipeline)
=========================================

An example Sinatra app configured with the Sprockets 2 asset pipeline. A custom guard file is available to run the asset pipeline precompiler whenever an asset changes.

**In this fork of sinatra-asset-pipeline, I've setup the project using [sprockets-helpers](https://github.com/petebrowne/sprockets-helpers) and [sprockets-sass](https://github.com/petebrowne/sprockets-sass).**

To run:

``` bash
$ bundle install
$ bundle exec guard
$ bundle exec rackup
```

And visit <http://localhost:9292>
