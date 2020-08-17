# Preact Quickstart
> Template project for a basic Preact app with the default setup


[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/preact-quickstart)](https://github.com/MichaelCurrin/preact-quickstart/tags/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)

[![npm preact](https://img.shields.io/badge/npm-preact-blue)](https://www.npmjs.com/package/preact)

[![Use this template](https://img.shields.io/badge/Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/preact-quickstart/generate)


## What is Preact?

From [preactjs.com](https://preactjs.com):

> Fast 3kB alternative to React with the same modern API.

If you are new to Preact, see the [Getting Start](https://preactjs.com/guide/v10/getting-started) page of the docs.

The whole point of Preact is that it is very small and light package that gives most of the React functionality. If you use few or no dependencies already and want to keep your project fast, then Preact is a great fit. You can even use it to on the frontend only to add a widget to page.

The problems comes in when you add other packages to your project as well that are bigger than Preact - then your footprint for JS assets the user has to download becomes bloated and you might as well use React. 

This quickstart project uses over 1600 dependencies once prod and dev dependencies are installed. So that might default the point of choosing Preact over React. If you do a prod install (`npm i --only=prod`) then only 4 packages get installed (one not in direct dependencies).

Preact also has great community support - check the online forums or Slack if you are stuck.


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

#### Notes

That install covers 3 production dependencies and 8 dev dependenciest that come in [package.json](/package.json) 

On a first-time install of the generated quickstart, I got this output:

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
