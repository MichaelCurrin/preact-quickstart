# Preact Quickstart

Template project for an Node app built with Preact - [preactjs.com](https://preactjs.com).


[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/preact-quickstart)](https://github.com/MichaelCurrin/preact-quickstart/tags/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)

[![npm preact](https://img.shields.io/badge/npm-preact-blue)](https://www.npmjs.com/package/preact)

[![Use this template](https://img.shields.io/badge/Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/preact-quickstart/generate)


## Background

This project was generated using instructions in the [preact-cli](https://github.com/preactjs/preact-cli#readme) README file.

```sh
$ npx preact-cli create default my-project
```

The `default` value was used here. The repo's doc linked above covers other options.


## Installation

### Install system dependencies

Install [Node.js](https://gist.github.com/MichaelCurrin/aa1fc56419a355972b96bce23f3bccba).

### Clone

Clone this project.

```sh
$ git clone git@github.com:MichaelCurrin/preact-quickstart.git
$ cd preact-quickstart
```

### Install project dependencies

```sh
$ npm install
```

This covers 3 production dependencies and 8 dev dependenciest that come in [package.json](/package.json) 

On a firstt-time install of the generated quickstart, I got this output:

```
added 1649 packages from 803 contributors and audited 1649 packages in 84.978s
```


## Usage

### Dev

Serve with hot reload at localhost:8080.

```sh
$ npm run dev
```

### Production

Build to the `build` directory (created if it doesn't yet exist).

```sh
$ npm run build
```

Test the production build locally (above step must be run first).

```sh
$ npm run serve
```

### Tests

Run tests with jest and enzyme.

```sh
$ npm run test
```


## License

Released under [MIT](/LICENSE).

Based on the CLI quickstart output which includes the default setup here:

- https://github.com/preactjs-templates/default

See the [source license](/LICENSE-source).
