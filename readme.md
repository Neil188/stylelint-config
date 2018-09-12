# stylelint-config

[![npm version](https://img.shields.io/npm/v/@neil188/stylelint-config.svg?style=popout)](https://www.npmjs.com/package/@neil188/stylelint-config)
[![Travis build](https://img.shields.io/travis/Neil188/stylelint-config/master.svg?style=popout)](https://travis-ci.org/Neil188/stylelint-config)
[![NpmLicense](https://img.shields.io/npm/l/@neil188/stylelint-config.svg?style=popout)](https://www.npmjs.com/package/@neil188/stylelint-config)
[![GitHub last commit (master)](https://img.shields.io/github/last-commit/neil188/stylelint-config/master.svg?style=popout)](https://github.com/Neil188/stylelint-config)

Stylelint rules for my personal projects.

## Usage

Install using:

```bash
npm install --save-dev @neil188/stylelint-config
```

Note: The following are included in this package so you don't need to install them yourself:

* stylelint
* stylelint-a11y
* stylelint-order
* stylelint-no-unsupported-browser-features
* @neil188/browserslist-config

Then in your Stylelint config file extend the rules:

```js
module.exports = {
    'extends': [
        '@neil188/stylelint-config'
    ]
};
```

in package.json add the browsersList entry:

```json
  "browserslist": [
    "extends @neil188/browserslist-config"
  ]
```

## LICENSE

MIT
