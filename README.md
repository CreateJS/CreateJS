### 2.0 BETA

**This repo is in beta. Reporting issues is appreciated.**

<p align="center">
  <a href="https://createjs.com">
    <img alt="createjs" src="https://raw.githubusercontent.com/createjs/createjs/master/assets/github-header.png" width="546">
  </a>
</p>

This package compiles the combined bundles for CDN distribution. It is mostly for internal use.

## Usage

Install dependencies prior to compiling builds.
```
npm install
```

It's recommended that you use `npm link` to compile from local packages.

###### `npm run build -- [--production] [--format=global,module,common]`

- combined builds with flag control for custom output

###### `npm run build-prod`

- combined build restricted to minified global format for the CDN
