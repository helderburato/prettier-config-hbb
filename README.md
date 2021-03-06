<div align="center">
  <h1>⚙️ prettier-config-hbb</h1>

  <p><strong>prettier-config-hbb is an opinionated configuration</strong> that makes it easy to start your projects.</p>

<!-- prettier-ignore-start -->
[![version][version-badge]][package]
[![license][license-badge]][license]
[![downloads][downloads-badge]][npmtrends]
[![gh-release][gh-release-badge]][gh-release]
<!-- prettier-ignore-end -->

</div>

---

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Motivation](#motivation)
- [Installation](#installation)
- [Usage](#usage)
  - [Override Configurations](#override-configurations)
  - [Scripts](#scripts)
- [Contributing](#contributing)
- [Bugs and Sugestions](#bugs-and-sugestions)
- [LICENSE](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Motivation

- Easy to start coding, avoid wasting time configuring for every project
- Focus on the project instead of the tooling
- Start the project quickly and easy

## Installation

This module is distributed by NPM and should be installed as one of your project's `devDependencies`:

```sh
$ npm install --save-dev prettier-config-hbb

// or

$ yarn add -D prettier-config-hbb
```

## Usage

Import to your `.prettierrc.js` such as:

```js
module.exports = require('prettier-config-hbb');
```

### Override Configurations

```js
const config = require('prettier-config-hbb');

module.exports = {
  ...config,
  semi: false,
};
```

### Scripts

Add the following to your package.json:

```json
"scripts": {
  "format": "prettier --write ."
},
```

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Bugs and Sugestions

Report bugs or do suggestions using the [issues](https://github.com/helderburato/prettier-config-hbb/issues).

## LICENSE

[MIT](LICENSE) @ Helder Burato Berto [HBB]

<!-- prettier-ignore-start -->
[version-badge]: https://img.shields.io/npm/v/prettier-config-hbb.svg?style=flat-square
[package]: https://www.npmjs.com/package/prettier-config-hbb
[downloads-badge]: https://img.shields.io/npm/dm/prettier-config-hbb.svg?style=flat-square
[npmtrends]: http://www.npmtrends.com/prettier-config-hbb
[license-badge]: https://img.shields.io/npm/l/prettier-config-hbb.svg?style=flat-square
[license]: https://github.com/helderburato/prettier-config-hbb/blob/master/LICENSE
[gh-release]: https://github.com/helderburato/prettier-config-hbb/actions/workflows/release.yml
[gh-release-badge]: https://github.com/helderburato/prettier-config-hbb/actions/workflows/release.yml/badge.svg
<!-- prettier-ignore-end -->
