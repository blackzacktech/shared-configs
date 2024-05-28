![Prettier config](https://api.yurna.info/assets/a7ed65fe-357a-440f-b290-b021dbec6d6a)

### 📥 Installation

```bash
npm install --save-dev @blackzacktech/prettier-config
yarn add --dev @blackzacktech/prettier-config
pnpm install --save-dev @blackzacktech/prettier-config
```

### 🔩 Usage

```js
// .prettierrc.js
module.exports = {
 ...require("@blackzacktech/prettier-config"),
};
```

```js
// prettier.config.js
import prettierConfig from "@blackzacktech/prettier-config";

export default {
  ...prettierConfig,
};
```

```json
{
  "extends": "@blackzacktech/prettier-config"
}
```

### ⚙️ Rules overview

<!--START_SECTION:prettier-->
| Rule                         | Style       | Documentation                                                                          |
| ---------------------------- | ----------- | -------------------------------------------------------------------------------------- |
| `arrowParens`                | `always`    | [Documentation](https://prettier.io/docs/en/options.html#arrow-parens)                 |
| `bracketSpacing`             | `true`      | [Documentation](https://prettier.io/docs/en/options.html#bracket-spacing)              |
| `embeddedLanguageFormatting` | `auto`      | [Documentation](https://prettier.io/docs/en/options.html#embedded-language-formatting) |
| `htmlWhitespaceSensitivity`  | `css`       | [Documentation](https://prettier.io/docs/en/options.html#html-whitespace-sensitivity)  |
| `jsxSingleQuote`             | `false`     | [Documentation](https://prettier.io/docs/en/options.html#jsx-single-quote)             |
| `printWidth`                 | `200000`    | [Documentation](https://prettier.io/docs/en/options.html#print-width)                  |
| `proseWrap`                  | `preserve`  | [Documentation](https://prettier.io/docs/en/options.html#prose-wrap)                   |
| `quoteProps`                 | `as-needed` | [Documentation](https://prettier.io/docs/en/options.html#quote-props)                  |
| `requirePragma`              | `false`     | [Documentation](https://prettier.io/docs/en/options.html#require-pragma)               |
| `semi`                       | `true`      | [Documentation](https://prettier.io/docs/en/options.html#semi)                         |
| `singleQuote`                | `false`     | [Documentation](https://prettier.io/docs/en/options.html#single-quote)                 |
| `tabWidth`                   | `1`         | [Documentation](https://prettier.io/docs/en/options.html#tab-width)                    |
| `trailingComma`              | `es5`       | [Documentation](https://prettier.io/docs/en/options.html#trailing-comma)               |
| `useTabs`                    | `false`     | [Documentation](https://prettier.io/docs/en/options.html#use-tabs)                     |
<!--END_SECTION:prettier-->
