# Without A Path - Admin notes

Welcome to the exciting world of Jekyll! It's not as visual as WordPress but it's a whole lot faster and fancier. Here are some notes to refer to as you go down this journey.

The nonprod url on Github Pages is [https://baurjoe.github.io/WithoutAPath/](https://baurjoe.github.io/WithoutAPath/)

## Common commands

To rebuild the site `jekyll build`

To serve the site locally `bundle exec jekyll serve`

To clean the cache `jekyll clean`

To search for errors `jekyl doctor`

## Index new searches

Whenever you publish new content you might need to index it into the search database. To do that, type this in to Terminal: 

`ALGOLIA_API_KEY='e9bcf425c4492d3c50cb0388b79417ca' bundle exec jekyll algolia`

