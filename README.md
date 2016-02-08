# This site is to commemorate Richard O'Beirne


## How to run

First make sure you have Ruby installed. If you're on OSX, make sure you have
a version of ruby that will allow you to install gems. Either run `bundle
install` if you have bundler, or manually install all of the gems listed in
`Gemfile`. After that, run `jekyll serve` and hit `localhost:4000`.


## How to develop

This is a pretty straightforward Jekyll site that aims to keep data and views
separate. If you have any kind of structured data, make a yml file in `_data`.
Re-used components should go in _includes, otherwise feel free to make pages as
you see fit as HTML files in the root directory. Given that this isn't a blog,
there'll be no need for a `_posts` directory unless anything changes.

### CSS

Nothing too fancy here, just SASS with Bourbon mixins. Try to keep your styles
broken out in to organized files in `_sass`. Don't forget to import them in
`css/main.scss`, otherwise they won't be included.

### Javascript

None yet, but maybe try coffeescript if you're feeling frisky.

### Images

To keep it lean, make sure you keep originals in `/images/{folder}/` and then
also make smaller sized versions of those images in `/images/{folder}/{WxH}/`
or `/images/{folder}/{MaxSize}/` and link to those sizes as needed.
TODO: Write a script to do this resizing?

