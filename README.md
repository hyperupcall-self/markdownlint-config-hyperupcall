# markdownlint-config-hyperupcall

Edwin's [Stylelint](https://stylelint.io) configuration.

## Install

```sh
pnpm i -D @hyperupcall/markdownlint-config
```

## Usage

In `.markdownlintrc.cjs`:

```js
module.exports = require('@hyperupcall/markdownlint-config')
```

In `.markdownlintrc.mjs`:

```js
import markdownlintConfig from '@hyperupcall/markdownlint-config'

export default markdownlintConfig
```
