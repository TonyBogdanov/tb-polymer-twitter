# tb-polymer-twitter

[![Build Status](https://travis-ci.org/TonyBogdanov/tb-polymer-twitter.svg?branch=master)](https://travis-ci.org/TonyBogdanov/tb-polymer-twitter)
[![Buy Me a Coffee](http://static.tonybogdanov.com/github/coffee.svg)](http://ko-fi.co/1236KUKJNC96B)

[Demo & Documentation](http://tonybogdanov.github.io/tb-polymer-twitter/components/tb-polymer-twitter/) |
[Tests](http://tonybogdanov.github.io/tb-polymer-twitter/components/tb-polymer-twitter/test/)

`<tb-polymer-twitter>` provides a flexible and extensible "widget"-like element for displaying twitter feeds
based on this [API](http://api.tonybogdanov.com) and [Polymer](http://polymer-project.org).

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, it's recommended that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at `http://localhost:8080/components/tb-polymer-twitter/`.


## Testing Your Element

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/tb-polymer-twitter/test/`

### web-component-tester

The tests are also compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.
