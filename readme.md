# stylelint-config

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
