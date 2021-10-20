# Product Name
> Short blurb about what your product does.

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

One to two paragraph statement about your product and what it does.

![](header.png)

## Installation

OS X & Linux:

```sh
npm install my-crazy-module --save
```

Windows:

```sh
edit autoexec.bat
```

## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
npm test
```

## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Your Name – [@YourTwitter](https://twitter.com/dbader_org) – YourEmail@example.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## Respectful Code
(copied from [Google V8](https://v8.dev/docs/respectful-code))
<!-- TODO: Should rework to make my own. -->

Inclusivity is central to Product X’s culture, and our values include treating each other with dignity. As such, it’s important that everyone can contribute without facing the harmful effects of bias and discrimination. However, terms in our codebase, UIs, and documentation can perpetuate that discrimination. This document sets forth guidance which aims to address disrespectful terminology in code and documentation.

### Policy 
Terminology that is derogatory, hurtful, or perpetuates discrimination, either directly or indirectly, should be avoided.

### Scope for this policy?
Anything that a contributor would read while working on Product X, including:

- Names of variables, types, functions, files, build rules, binaries, exported variables, ...
- Test data
- System output and displays
- Documentation (both inside and outside of source files)
- Commit messages

### Principles
- Be respectful: derogatory language shouldn’t be necessary to describe how things work.
- Respect culturally sensitive language: some words may carry significant historical or political meanings. Please be mindful of this and use alternatives.

### Example of terminology to be avoided?
This list is NOT meant to be comprehensive. It contains a few examples that people have run into frequently.

|    Term   |                     Suggested alternatives                    |
|:---------:|:-------------------------------------------------------------:|
| master    | primary, controller, leader, host                             |
| slave     | replica, subordinate, secondary, follower, device, peripheral |
| whitelist | allowlist, exception list, inclusion list                     |
| blacklist | denylist, blocklist, exclusion list                           |
| insane    | unexpected, catastrophic, incoherent                          |
| sane      | expected, appropriate, sensible, valid                        |
| crazy     | unexpected, catastrophic, incoherent                          |
| redline   | priority line, limit, soft limit                              |

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
