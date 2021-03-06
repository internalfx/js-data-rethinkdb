# Contributing Guide

First, support is handled via the [Gitter Channel](https://gitter.im/js-data/js-data) and the [Mailing List](https://groups.io/org/groupsio/jsdata). Ask your questions there.

When submitting issues on GitHub, please include as much detail as possible to make debugging quick and easy.

- good - Your versions of js-data, js-data-rethinkdb, etc., relevant console logs/error, code examples that revealed the issue
- better - A [plnkr](http://plnkr.co/), [fiddle](http://jsfiddle.net/), or [bin](http://jsbin.com/?html,output) that demonstrates the issue
- best - A Pull Request that fixes the issue, including test coverage for the issue and the fix

[Github Issues](https://github.com/js-data/js-data-rethinkdb/issues).

#### Submitting Pull Requests

1. Contribute to the issue/discussion that is the reason you'll be developing in the first place
1. Fork js-data-rethinkdb
1. `git clone git@github.com:<you>/js-data-rethinkdb.git`
1. `cd js-data-rethinkdb; npm install; bower install;`
1. Write your code, including relevant documentation and tests
1. Run `grunt test` (build and test)
1. Your code will be linted and checked for formatting, the tests will be run
1. The `dist/` folder & files will be generated, do NOT commit `dist/*`! They will be committed when a release is cut.
1. Submit your PR and we'll review!
1. Thanks!
