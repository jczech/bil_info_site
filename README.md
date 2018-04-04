# Virtual Volume File System Site

## Overview

This is just a flashy little webpage to advertise the VVFS. It's pretty light
on content at the moment, and there is still some placeholder lorem ipsum text
that needs replaced.

## How to Use

It's probably easiest to use rvm (ruby version manager), but you can probably
do this with whatever version of ruby that is available in your package
manager.

  * Installing rvm by running the following commands
    * `gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB`
    * `\curl -sSL https://get.rvm.io | bash -s stable`
    * You might need to source rmv like this: `source ~/.rvm/scripts/rv` 
  * Install and enable a recent version of ruby with rvm
    * `rvm install 2.4.1`
    * `rvm use 2.4.1`
  * Install jekyll and bundler and other dependencies
    * `gem install jekyll`
    * `gem install bundler`
    * `bundle install`
  * Serve page 
    * `jekyll serve`
    * It is served on port 4000 by default (point browser to 127.0.0.1:4000)


## Original README Notes

A Jekyll port of the Spectral theme by HTML5 UP.
Find the original non-jekyll theme at: http://html5up.net/
Note: @arkadianriver is in no way associated with @n33co
      other than I really like his _style_! get it?
Below is @n33co's readme from the original pure HTML theme


Spectral by HTML5 UP
html5up.net | @n33co
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


A big, modern, blocky affair with a mobile-style menu, fully responsive styling,
and an assortment of pre-styled elements. So, pretty much what you were expecting
-- except, of course, for how it's put together, specifically:

- It's built on Skel 3\*, a leaner, more modular rewrite of my responsive framework.

  (\* = still in development as of this writing)

- It uses flexbox\*, which eliminates all kinds of terrible hacks and clunky layout
  stopgaps (like CSS grid systems).

  (\* = not supported on IE8/9, but non-flexbox fallbacks are included)

- It uses Sass\* a lot more intelligently, thanks in part to several new mixins
  and functions I've been working on (as well as a few by @HugoGiraudel).

  (\* = still entirely optional if you prefer vanilla CSS :)

- A ton of other stuff.

In short, Spectral's the culmination of several new things I'm working on/trying out,
so please, let me know what you think :)

Demo images\* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(\* = not included)

AJ
n33.co @n33co dribbble.com/n33


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		background-size polyfill (github.com/louisremi)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
