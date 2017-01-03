# fish-names

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

### .random()

Type: `function`

Returns a random fish name
