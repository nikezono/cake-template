node-combine-rss
---

combine rss feeds in url

input multiple rss feeds, then output single xml url

combined rss object can deal like below.

##install

***using npm:***

    npm install combine-rss

****or using package.json:***

    "combine-rss": "*"

##usage
    # Coffeescript
    finder = require 'find-rss'
    finder "http://www.apple.com/",(candidates)->
      console.log candidates

      # =>
      # [ { rel: 'alternate',
            type: 'application/rss+xml',
            title: 'RSS',
            href: 'http://images.apple.com/main/rss/hotnews/hotnews.rss',
            url: 'http://images.apple.com/main/rss/hotnews/hotnews.rss' } ]
