rspec.github.io
===============

Source for https://rspec.info

Requires a recent version of Ruby (tested on 2.5.3), bundler and imagemagick (to generate favicons).

## Local Setup

* `brew install imagemagick` (or your package manager of choice).
* `bundle install`
* `middleman build`

## Local Developing

Run `LIVERELOAD=true middleman server`

## Docker Setup + Development

If you don't have a local Ruby environment suitable to making changes to rspec.info,
or prefer containerised development; you can find a 3rd party Docker image setup for
this environment here: https://hub.docker.com/r/2performantirina/middleman-and-imagemagick

## Deploying

Run `bundle exec middleman build`, which will compile the site to `docs`.

To deploy to staging you can create a PR against https://github.com/RSpec-Staging/rspec-staging.github.io/.

To deploy to production you should create a PR against https://github.com/rspec/rspec.github.io/.

## Credits

[Andrew Harvey](https://mootpointer.com) - for his incredible effort of making this repository as it is now
