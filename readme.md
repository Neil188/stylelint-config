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

Then in your Stylelint config file extend the rules:

```js
module.exports = {
    'extends': [
        '@neil188/stylelint-config'
    ]
};
```

## LICENSE

MIT
