# Preact Quickstart
> Template project for a basic Preact app with the default setup

[![Node CI](https://github.com/MichaelCurrin/preact-quickstart/workflows/Node%20CI/badge.svg)](https://github.com/MichaelCurrin/preact-quickstart/actions)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/preact-quickstart)](https://github.com/MichaelCurrin/preact-quickstart/tags/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node](https://img.shields.io/badge/Node.js->=10-blue?logo=node.js&logoColor=white)](https://nodejs.org)
[![Package - preact](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/preact-quickstart/preact)](https://www.npmjs.com/package/preact)



## Preview

<div align="center">
    <img src=sample.png alt="Sample screenshot" title="Sample screenshot" height="400" />
</div>


## Use this project

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/preact-quickstart/generate)

</div>


## About Preact

### What is Preact?

From the [preactjs.com](https://preactjs.com) homepage:

> Fast 3kB alternative to React with the same modern API.

If you are new to Preact, see the [Getting Started](https://preactjs.com/guide/v10/getting-started) page of the docs.

### Why Preact?

The whole point of Preact is that it is very small and light package that gives most of the React functionality. If you use few or no dependencies already and want to keep your project fast, then Preact is a great fit. You can even use it to on the frontend only to add a widget to page.

The problems comes in when you add other packages to your project as well that are bigger than Preact - then your footprint for JS assets the user has to download becomes bloated and you might as well use React.

This quickstart project uses over 1600 dependencies once prod and dev dependencies are installed. So that might default the point of choosing Preact over React. If you do a prod install (`npm i --only=prod`) then only 4 packages get installed (one not in direct dependencies).

Preact also has great community support - check the online forums or Slack if you are stuck.

### How does it compare to React?

Preact is supposed to cover most functionality in React that you're likely to need.

Preact and React code looks very similar. One difference is that you can use `class` on element in Preact, while in React you need `className`.

Check out my [React Quickstart](https://github.com/MichaelCurrin/preact-quickstart) repo to compare how a basic app is structured in each library.

Preact needs its own plugins though. Unless you can configure a React plugin to look for Preact.


## Create a fresh project

This project was generated using instructions in the [preact-cli](https://github.com/preactjs/preact-cli#readme) README file.

You can do the same with:

```sh
$ npx preact-cli create default my-project
```

The `default` value was used here. The  page linked above covers other options.

Creating a new project will give you code that might be more up to date than this Preact Quickstart template project. But you can still use this template project as a reference for sample documentation and a CI workflow for your own project.


## Installation

### Install system dependencies

Install [Node.js](https://gist.github.com/MichaelCurrin/aa1fc56419a355972b96bce23f3bccba).

### Clone

Clone this project:

```sh
$ git clone git@github.com:MichaelCurrin/preact-quickstart.git
$ cd preact-quickstart
```

### Install project dependencies

```sh
$ npm install
```

#### Notes

That install commands covers 3 production dependencies and 8 dev dependencies - see [package.json](/package.json)

On a first-time install of the generated quickstart, I got this output:

```
added 1649 packages from 803 contributors and audited 1649 packages in 84.978s
```

A few months later, this was higher:

```
audited 2270 packages in 15.531s
```

So yes, Preact is light on your frontend for your user, but you still get a ton of local dependencies to manage.


## Usage

### Lint

Lint with ESLint.

```sh
$ npm run lint
```

### Tests

Run tests using `jest` and `enzyme`.

```sh
$ npm test
```

### Start dev server

Serve with hot-reloading.

```sh
$ npm start
```

Open the browser at:

- [localhost:8080](https://localhost:8080)


## Deploy

### Local production build

Build to the unversioned `build` directory.

```sh
$ npm run build
```

Start a static server in that directory.

```sh
$ npm run serve
```

### Deploy pipeline

This project is setup to run a CI/CD builds on GitHub pages. See the _Actions_ tab on the repo for build status and logs.

See the [workflow config](/.github/workflows/main.yml) file.

The build is not persisted and served on GH Pages, however, this [React quickstart](https://github.com/MichaelCurrin/react-create-app-quickstart) projects does do that and so that can be brought in here if needed.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).

This project is based on the CLI quickstart output which includes the default setup here:

[![preactjs-templates - default](https://img.shields.io/static/v1?label=preactjs-templates&message=default&color=blue&logo=github)](https://github.com/preactjs-templates/default)

See the [source license](/LICENSE-source).
