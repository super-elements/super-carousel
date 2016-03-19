# super-carousel

The only carousel Web Component you will ever need!

## Work in Progress

Work on `super-carousel` has only *just started*! We recommend that **no one** use it in production now!

## Roadmap

The plan is for `super-carousel` to be used in production in a variety of Mobile and Desktop environments. The element will cease to be a **thin** wrapper around Slick and will be a full blown carousel having a rich API soon!

## Attributes

The element has a single attribute called `settings` where we pass a JSON having keys from http://kenwheeler.github.io/slick/#settings

## Dependencies

Currently, `super-carousel` is a **thin** wrapper around [Slick](http://kenwheeler.github.io/slick/).
You will need to include jQuery (not included in the element).

Slick is included in the element's `bower.json` and gets installed along with the element.

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install
