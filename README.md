# fish-names [![Build Status](https://travis-ci.org/yeskunall/fish-names.svg?branch=master)](https://travis-ci.org/yeskunall/fish-names) [![npm](https://img.shields.io/npm/dt/fish-names.svg)](http://npm.im/fish-names) [![Codecov](https://img.shields.io/codecov/c/github/yeskunall/fish-names.svg)]()

> Get popular fish names 🐟 🐡

__Accepting PRs for additional names.__

## Install

```
$ npm install --save fish-names
```

## Usage

```js
const fishNames = require('fish-names');

fishNames.random();
//=> 'Lucy'
```

## API

### .all

Type: `array`

Lists all 200 popular fish names

### .allMaleFish

Type: `array`

Lists all popular male fish names

### .allFemaleFish

Type: `array`

Lists all popular female fish names

### .random(n: Number)

Type: `function`

Returns a random fish name, if no param is provided. Otherwise, returns an array of random fish of length `n`

### .getMaleFish(n: Number)

Type: `function`

Returns a random male fish name, if no param is provided. Otherwise, returns an array of random male fish of length `n`

### .getFemaleFish(n: Number)

Type: `function`

Returns a random female fish name, if no param is provided. Otherwise, returns an array of random female fish of length `n`

