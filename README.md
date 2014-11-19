react-leaf
==========

A starter repository for using React with the Siteleaf CMS.

## What is this?
This repo exposes the Siteleaf site data as a json object on the
window at window.siteData. From here we can feed the content directly
into react and have it populate the DOM for us. Neat huh?

For some reason siteleaf neither exposes the site as an object nor allows
recursive templating so for now I am scaffolding out the data manually.

NB. Not all siteleaf fields are included in _data.html


## Instructions
- Install the Siteleaf gem
- Authorise the gem with `siteleaf auth`
- Create a new site via `siteleaf new DOMAIN` or link to an existing one with `siteleaf config DOMAIN`
- Run the siteleaf server via `siteleaf server`
- Navigate to `localhost:9292` you should see all accessible data

## Thanks
Big ups to [Mr Maximillion Wheeler](http://github.com/makenosound) for helping me get this setup in
the first place.
