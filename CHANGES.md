## Version 4.0.0, 2017.06.09

* Rename library to Europa :new_moon: and move package from `html-md` to `europa`
* Rewrite entire code base from ground up and adopt OOP pattern (no more CoffeeScript)
* Release fresh code base under MIT license
* Split into multiple modules (`europa` for browser, `node-europa` for Node.js, `europa-core` to support all environments, `europa-test` for testing)
* Add support for plugins (and the concept of presets)
* Restructure code base to make it more maintainable
* Remove documentation generated by `docco`
* Add `.editorconfig` to help contributors using compatible editors
* Remove `INSTALL.md` and consolidate contents into `README.md` and `CONTRIBUTING.md`
* Switch to container-based Travis builds for faster boot times
* Remove `noConflict` method
* Remove `version` field

### Specific to `europa-test`

* Create `europa-test` framework to help test `europa-core` implementations
* Replace `nodeunit` with `mocha` and `chai`

## Version 3.1.0, 2016.09.02

* Fix support for AMD [#39](https://github.com/NotNinja/europa/issues/39)
* Correct license to GPL-2.0 [#66](https://github.com/NotNinja/europa/issues/66)

## Version 3.0.2, 2013.10.09

* Fix errors in Internet Explorer 8 and older [#36](https://github.com/NotNinja/europa/issues/36)
* Fix problem with running command line [#37](https://github.com/NotNinja/europa/issues/37)
* Update versions on dependencies
* Minor changes and tweaks

## Version 3.0.1, 2013.08.16

* Fix handling of unformatted HTML lists [#33](https://github.com/NotNinja/europa/issues/33)

## Version 3.0.0, 2013.08.15

* Rename command from `md` to `html-md` [#30](https://github.com/NotNinja/europa/issues/30)
* Correct expectations of void elements [#31](https://github.com/NotNinja/europa/issues/31)
* Update versions of dependencies

## Version 2.1.1, 2013.05.06

* Add `base` option to specify the base URL used to resolve relative URLs [#24](https://github.com/NotNinja/europa/issues/24)

## Version 2.1.0, 2013.05.03

* Add support for [bower](http://twitter.github.io/bower/) installations [#18](https://github.com/NotNinja/europa/issues/18)
* Replace `Cakefile` with new [grunt](http://gruntjs.com) build process [#20](https://github.com/NotNinja/europa/issues/20)
* Replace [tap](https://github.com/isaacs/node-tap) test framework with [nodeunit](https://github.com/caolan/nodeunit) [#20](https://github.com/NotNinja/europa/issues/20)
* Remove [CoffeeScript](http://coffeescript.org) as a runtime dependency [#21](https://github.com/NotNinja/europa/issues/21)
* Update [jsdom](https://github.com/tmpvar/jsdom) to v0.6.0 to fix known bugs [#21](https://github.com/NotNinja/europa/issues/21)
* Improve compatibility with the Windows platform [#21](https://github.com/NotNinja/europa/issues/21)
* Improve code and documentation quality and standards [#21](https://github.com/NotNinja/europa/issues/21)
* Fix `absolute` option to also apply to `img` elements [#21](https://github.com/NotNinja/europa/issues/21)
* Improve compatibility with older browsers [#21](https://github.com/NotNinja/europa/issues/21)
* Improve handling of ordered and unordered lists [#22](https://github.com/NotNinja/europa/issues/22)
* Support nested lists [#22](https://github.com/NotNinja/europa/issues/22)
* Add option to support inline link style [#23](https://github.com/NotNinja/europa/issues/23)
* Replace [optparse](https://github.com/jfd/optparse-js) with [commander](http://visionmedia.github.io/commander.js/)
* Lots of bug fixes and optimizations

## Version 2.0.2, 2013.02.04

* Add new man page [#13](https://github.com/NotNinja/europa/issues/13)
* Fix bug with `eval` option [#14](https://github.com/NotNinja/europa/issues/14)

## Version 2.0.1, 2012.12.12

* Fix incorrect version [#8](https://github.com/NotNinja/europa/issues/8)

## Version 2.0.0, 2012.12.11

* Check inline style attribute to see if elements are hidden [#1](https://github.com/NotNinja/europa/issues/1)
* Add command line interface [#2](https://github.com/NotNinja/europa/issues/2)
* Create unit test suite [#3](https://github.com/NotNinja/europa/issues/3)
* Rewrite code in CoffeeScript [#4](https://github.com/NotNinja/europa/issues/4)
* Add compatibility support for node.js [#5](https://github.com/NotNinja/europa/issues/5)
* Add build process [#6](https://github.com/NotNinja/europa/issues/6)
