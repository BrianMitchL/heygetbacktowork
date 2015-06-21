# Hey, Get Back to Work!
Source of [heygetbackto.work](http://heygetbackto.work)

A place to remind you to work.

## Contributing
Feel free to submit a pull request with a new page of wonderfully useless animation or time wasting content. Please add a link to the new page on the main index.html file. Please try to match the same coding style if you can, or submit an issue with any suggestions.

To add a new page, simply create a new directory at the root level with the name of the route, and add an HTML file named index.html inside. Add the following to the top, and everything underneath will be inserted into the body tag.
```
---
layout: default
---
```

To view your changes and run the webserver, install bundler and the dependencies for the project. Note: you may need to be root or use sudo.
```sh
gem install bundler
bundle install
```

To start the server, run
```
jekyll serve
```

## Attributions
* Gradient adapted from [Animated Background Gradient](http://codepen.io/quasimondo/pen/lDdrF/) by [Mario Klingemann](http://codepen.io/quasimondo/).
* Animation used from [animate.css](https://github.com/daneden/animate.css) by [Daniel Eden](http://daneden.me/).
