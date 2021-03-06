Rails 4 API
===========

[![Build Status](https://travis-ci.org/emilsoman/rails-4-api.png)](https://travis-ci.org/emilsoman/rails-4-api)

After I published my blog post on [Building a Tested, Documented and Versioned JSON API Using Rails 4](http://www.emilsoman.com/blog/2013/05/18/building-a-tested/),
many readers asked me for a sample app which can act as a template. So here it is. Feel free to send in pull requests.

This is a template Rails 4 app which has the following to start with :

1. Rails-API - Rails for API only apps
2. Devise for token based authentication
3. Cucumber for integration testing + up-to-date API documentation
4. Versioning using the "Accept" header
5. Does not depend on cookies/session.( In simple words, the API client need not be a browser )

## Getting started

    cd rails-4-api
    bundle install --without production
    bundle exec rake #Build ( RSpec + Cucumber )
    #open public/api_doc.html in your browser

