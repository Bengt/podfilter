http://www.podfilter.de


## Contribute:

Needs redis, imagemagick and postgresql on your host.

Fork, install/configure:

```
git clone https://github.com/YOURFORK/podfilter.de
cd podfilter.de
bundle
rake db:migrate db:test:prepare
bundle exec rspec

rake db:seed

foreman start
# navigate to http://localhost:5000
# sidekiq background worker is also started
```


### What could be done?

* search
* categorization improvements
* recommendations
* Twitter/ more oauth login
* Stylings
* OPML Export
* Take part without providing a OPML, e.g. by manually liking episodes
* more community/comment/like aspects

* follow redirects. example http://learn.thoughtbot.com/podcast.xml
* remove duplicates -> similar mp3/ogg links unification
