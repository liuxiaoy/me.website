Materialize - jekyll
==============


## Introducton

This jekyll theme is based on [materialize](http://materializecss.com).
[Open demo](https://mumuxme.github.io/materialize-jekyll/)


## Getting start

1. Modify `_config.yml`, `about.md` and other(whatever you need).
2. You can add a `favicon.ico` file in the project root directory.
3. If you want to use google analytics, add your `google-analytics.js` into `js` directory.

Then:

```
$ bundle exec jekyll s

# or start with draft
$ bundle exec jekyll s --drafts
```

## Or start with docker

```
cd materialize-jekyll

# export GEM_MIRROR=mirror.https://rubygems.org
export GEM_MIRROR='Your-ruby-gem-mirror'

make build
make run
```
