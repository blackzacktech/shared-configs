![Shared Configs](https://api.yurna.info/assets/9ebbd107-05b9-4324-b00e-1c284d91978f)

## ♻️ Shareable configs

| **Package** | **Version** | **Downloads** | **Documentation** |
| - | - | - | - |
| 📦 [`@blackzacktech/eslint-config`](https://npmjs.com/package/@blackzacktech/eslint-config) | ![](https://img.shields.io/npm/v/%40blackzacktech%2Feslint-config/latest.svg) | [![](https://img.shields.io/npm/dw/@blackzacktech/eslint-config)](https://npmjs.com/package/@blackzacktech/eslint-config) | [Documentation](/packages/eslint-config/README.md) |
| 📦 [`@blackzacktech/prettier-config`](https://npmjs.com/package/@blackzacktech/prettier-config) | ![](https://img.shields.io/npm/v/%40blackzacktech%2Fprettier-config/latest.svg) | [![](https://img.shields.io/npm/dw/@blackzacktech/prettier-config)](https://npmjs.com/package/@blackzacktech/prettier-config) | [Documentation](/packages/prettier-config/README.md) |
| 📝 [`@blackzacktech/renovate-config`](https://npmjs.com/package/@blackzacktech/prettier-config) | ![](https://img.shields.io/github/package-json/v/blackzacktech/shared-configs?filename=packages%2Frenovate-config%2Fpackage.json&label=github%40latest) | - | [Documentation](/packages/renovate-config/README.md) |

> [!NOTE]
> 📦 - Package  
> 📝 - Configuration file

---

## 📦 [`@blackzacktech/prettier-config`](https://www.npmjs.com/package/@blackzacktech/prettier-config)

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
  ...require('@blackzacktech/prettier-config'),
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

---

## 📦 [`@blackzacktech/eslint-config`](https://www.npmjs.com/package/@blackzacktech/eslint-config)

### 📥 Installation

```bash
npm install --save-dev @blackzacktech/eslint-config
yarn add --dev @blackzacktech/eslint-config
pnpm install --save-dev @blackzacktech/eslint-config
```


### 🔩 Usage

> [!IMPORTANT]
> Starting from version `2.0.0` this package now includes both [`legacy`](https://eslint.org/docs/latest/use/configure/configuration-files) and [`flat`](https://eslint.org/docs/latest/use/configure/configuration-files-new) configs. This is breaking change, so please update your config files accordingly.

**Legacy config:**
```js
// .eslintrc.js
module.exports = {
 extends: ["@blackzacktech/eslint-config/legacy"],
};
```

**Flat config:**
```js
// eslint.config.js
import eslintConfig from "@blackzacktech/eslint-config/flat";

export default [
 ...eslintConfig
];
```

<!-- ### ⚙️ Rules overview -->

<!--START_SECTION:eslint-->
| Rule                                             | Style                                                               | Type                  | Documentation                                                                    |
| ------------------------------------------------ | ------------------------------------------------------------------- | --------------------- | -------------------------------------------------------------------------------- |
| `constructor-super`                              | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/constructor-super)                 |
| `for-direction`                                  | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/for-direction)                     |
| `getter-return`                                  | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/getter-return)                     |
| `no-async-promise-executor`                      | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-async-promise-executor)         |
| `no-case-declarations`                           | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-case-declarations)              |
| `no-class-assign`                                | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-class-assign)                   |
| `no-compare-neg-zero`                            | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-compare-neg-zero)               |
| `no-cond-assign`                                 | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-cond-assign)                    |
| `no-const-assign`                                | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-const-assign)                   |
| `no-constant-binary-expression`                  | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-constant-binary-expression)     |
| `no-constant-condition`                          | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-constant-condition)             |
| `no-control-regex`                               | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-control-regex)                  |
| `no-debugger`                                    | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-debugger)                       |
| `no-delete-var`                                  | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-delete-var)                     |
| `no-dupe-args`                                   | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-dupe-args)                      |
| `no-dupe-class-members`                          | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-dupe-class-members)             |
| `no-dupe-else-if`                                | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-dupe-else-if)                   |
| `no-dupe-keys`                                   | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-dupe-keys)                      |
| `no-duplicate-case`                              | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-duplicate-case)                 |
| `no-empty`                                       | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-empty)                          |
| `no-empty-character-class`                       | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-empty-character-class)          |
| `no-empty-pattern`                               | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-empty-pattern)                  |
| `no-empty-static-block`                          | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-empty-static-block)             |
| `no-ex-assign`                                   | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-ex-assign)                      |
| `no-extra-boolean-cast`                          | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-extra-boolean-cast)             |
| `no-fallthrough`                                 | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-fallthrough)                    |
| `no-func-assign`                                 | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-func-assign)                    |
| `no-global-assign`                               | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-global-assign)                  |
| `no-import-assign`                               | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-import-assign)                  |
| `no-invalid-regexp`                              | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-invalid-regexp)                 |
| `no-irregular-whitespace`                        | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-irregular-whitespace)           |
| `no-loss-of-precision`                           | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-loss-of-precision)              |
| `no-misleading-character-class`                  | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-misleading-character-class)     |
| `no-new-native-nonconstructor`                   | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-new-native-nonconstructor)      |
| `no-nonoctal-decimal-escape`                     | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-nonoctal-decimal-escape)        |
| `no-obj-calls`                                   | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-obj-calls)                      |
| `no-octal`                                       | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-octal)                          |
| `no-prototype-builtins`                          | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-prototype-builtins)             |
| `no-redeclare`                                   | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-redeclare)                      |
| `no-regex-spaces`                                | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-regex-spaces)                   |
| `no-self-assign`                                 | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-self-assign)                    |
| `no-setter-return`                               | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-setter-return)                  |
| `no-shadow-restricted-names`                     | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-shadow-restricted-names)        |
| `no-sparse-arrays`                               | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-sparse-arrays)                  |
| `no-this-before-super`                           | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-this-before-super)              |
| `no-undef`                                       | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-undef)                          |
| `no-unexpected-multiline`                        | 0                                                                   | `undefined undefined` | [Documentation](https://eslint.org/docs/rules/no-unexpected-multiline)           |
| `no-unreachable`                                 | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-unreachable)                    |
| `no-unsafe-finally`                              | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-unsafe-finally)                 |
| `no-unsafe-negation`                             | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-unsafe-negation)                |
| `no-unsafe-optional-chaining`                    | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-unsafe-optional-chaining)       |
| `no-unused-labels`                               | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-unused-labels)                  |
| `no-unused-private-class-members`                | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-unused-private-class-members)   |
| `no-unused-vars`                                 | [Documentation](https://eslint.org/docs/rules/no-unused-vars)       | `⚠️ Warning`          | [Documentation](https://eslint.org/docs/rules/no-unused-vars)                    |
| `no-useless-backreference`                       | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-useless-backreference)          |
| `no-useless-catch`                               | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-useless-catch)                  |
| `no-useless-escape`                              | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-useless-escape)                 |
| `no-with`                                        | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-with)                           |
| `require-yield`                                  | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/require-yield)                     |
| `use-isnan`                                      | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/use-isnan)                         |
| `valid-typeof`                                   | [Documentation](https://eslint.org/docs/rules/valid-typeof)         | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/valid-typeof)                      |
| `import/order`                                   | -                                                                   | `⚠️ Warning`          | External rule                                                                    |
| `@stylistic/linebreak-style`                     | Unix                                                                | `🚫 Error`            | External rule                                                                    |
| `@stylistic/quotes`                              | Double                                                              | `🚫 Error`            | External rule                                                                    |
| `@stylistic/semi`                                | Always                                                              | `⚠️ Warning`          | External rule                                                                    |
| `@stylistic/comma-dangle`                        | -                                                                   | `🚫 Error`            | External rule                                                                    |
| `@stylistic/block-spacing`                       | Error                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/comma-spacing`                       | Error                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/keyword-spacing`                     | Error                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/space-infix-ops`                     | Error                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/space-unary-ops`                     | Error                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/brace-style`                         | Error                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/object-curly-spacing`                | Always                                                              | `🚫 Error`            | External rule                                                                    |
| `@stylistic/space-before-function-paren`         | -                                                                   | `🚫 Error`            | External rule                                                                    |
| `@stylistic/space-in-parens`                     | Never                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/array-bracket-spacing`               | Never                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/template-curly-spacing`              | Never                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/computed-property-spacing`           | Never                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/quote-props`                         | As-needed                                                           | `🚫 Error`            | External rule                                                                    |
| `@stylistic/no-extra-semi`                       | Error                                                               | `🚫 Error`            | External rule                                                                    |
| `@stylistic/jsx-quotes`                          | Prefer-double                                                       | `🚫 Error`            | External rule                                                                    |
| `no-lonely-if`                                   | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-lonely-if)                      |
| `no-object-constructor`                          | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-object-constructor)             |
| `no-use-before-define`                           | [Documentation](https://eslint.org/docs/rules/no-use-before-define) | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-use-before-define)              |
| `no-label-var`                                   | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-label-var)                      |
| `no-undefined`                                   | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-undefined)                      |
| `complexity`                                     | 50                                                                  | `⚠️ Warning`          | [Documentation](https://eslint.org/docs/rules/complexity)                        |
| `no-alert`                                       | Warn                                                                | `⚠️ Warning`          | [Documentation](https://eslint.org/docs/rules/no-alert)                          |
| `require-await`                                  | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/require-await)                     |
| `prefer-object-spread`                           | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/prefer-object-spread)              |
| `prefer-destructuring`                           | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/prefer-destructuring)              |
| `array-callback-return`                          | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/array-callback-return)             |
| `yoda`                                           | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/yoda)                              |
| `unicode-bom`                                    | Never                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/unicode-bom)                       |
| `no-process-env`                                 | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-process-env)                    |
| `no-eval`                                        | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/no-eval)                           |
| `func-names`                                     | As-needed                                                           | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/func-names)                        |
| `camelcase`                                      | [Documentation](https://eslint.org/docs/rules/camelcase)            | `⚠️ Warning`          | [Documentation](https://eslint.org/docs/rules/camelcase)                         |
| `prefer-const`                                   | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/prefer-const)                      |
| `object-shorthand`                               | Always                                                              | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/object-shorthand)                  |
| `no-process-exit`                                | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-process-exit)                   |
| `global-require`                                 | Error                                                               | `🚫 Error`            | [Documentation](https://eslint.org/docs/rules/global-require)                    |
| `curly`                                          | 0                                                                   | `undefined undefined` | [Documentation](https://eslint.org/docs/rules/curly)                             |
| `@typescript-eslint/lines-around-comment`        | 0                                                                   | `undefined undefined` | External rule                                                                    |
| `@typescript-eslint/quotes`                      | 0                                                                   | `undefined undefined` | External rule                                                                    |
| `babel/quotes`                                   | 0                                                                   | `undefined undefined` | External rule                                                                    |
| `unicorn/template-indent`                        | 0                                                                   | `undefined undefined` | External rule                                                                    |
| `vue/html-self-closing`                          | 0                                                                   | `undefined undefined` | External rule                                                                    |
| `vue/max-len`                                    | 0                                                                   | `undefined undefined` | External rule                                                                    |
| `@babel/object-curly-spacing`                    | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@babel/semi`                                    | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/block-spacing`               | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/brace-style`                 | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/comma-dangle`                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/comma-spacing`               | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/func-call-spacing`           | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/indent`                      | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/key-spacing`                 | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/keyword-spacing`             | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/member-delimiter-style`      | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/no-extra-parens`             | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/no-extra-semi`               | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/object-curly-spacing`        | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/semi`                        | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/space-before-blocks`         | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/space-before-function-paren` | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/space-infix-ops`             | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `@typescript-eslint/type-annotation-spacing`     | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `babel/object-curly-spacing`                     | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `babel/semi`                                     | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/boolean-style`                         | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/delimiter-dangle`                      | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/generic-spacing`                       | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/object-type-curly-spacing`             | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/object-type-delimiter`                 | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/quotes`                                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/semi`                                  | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/space-after-type-colon`                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/space-before-generic-bracket`          | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/space-before-type-colon`               | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `flowtype/union-intersection-spacing`            | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-child-element-spacing`                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-closing-bracket-location`             | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-closing-tag-location`                 | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-curly-newline`                        | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-curly-spacing`                        | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-equals-spacing`                       | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-first-prop-new-line`                  | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-indent`                               | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-indent-props`                         | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-max-props-per-line`                   | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-newline`                              | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-one-expression-per-line`              | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-props-no-multi-spaces`                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-tag-spacing`                          | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `react/jsx-wrap-multilines`                      | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `standard/array-bracket-even-spacing`            | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `standard/computed-property-even-spacing`        | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `standard/object-curly-even-spacing`             | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `unicorn/empty-brace-spaces`                     | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `unicorn/no-nested-ternary`                      | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `unicorn/number-literal-case`                    | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/array-bracket-newline`                      | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/array-bracket-spacing`                      | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/array-element-newline`                      | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/arrow-spacing`                              | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/block-spacing`                              | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/block-tag-newline`                          | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/brace-style`                                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/comma-dangle`                               | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/comma-spacing`                              | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/comma-style`                                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/dot-location`                               | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/func-call-spacing`                          | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/html-closing-bracket-newline`               | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/html-closing-bracket-spacing`               | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/html-end-tags`                              | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/html-indent`                                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/html-quotes`                                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/key-spacing`                                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/keyword-spacing`                            | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/max-attributes-per-line`                    | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/multiline-html-element-content-newline`     | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/multiline-ternary`                          | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/mustache-interpolation-spacing`             | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/no-extra-parens`                            | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/no-multi-spaces`                            | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/no-spaces-around-equal-signs-in-attribute`  | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/object-curly-newline`                       | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/object-curly-spacing`                       | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/object-property-newline`                    | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/operator-linebreak`                         | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/quote-props`                                | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/script-indent`                              | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/singleline-html-element-content-newline`    | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/space-in-parens`                            | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/space-infix-ops`                            | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/space-unary-ops`                            | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `vue/template-curly-spacing`                     | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `space-unary-word-ops`                           | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-unary-word-ops)              |
| `generator-star`                                 | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/generator-star)                    |
| `no-comma-dangle`                                | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-comma-dangle)                   |
| `no-reserved-keys`                               | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-reserved-keys)                  |
| `no-space-before-semi`                           | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-space-before-semi)              |
| `no-wrap-func`                                   | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-wrap-func)                      |
| `space-after-function-name`                      | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-after-function-name)         |
| `space-before-function-parentheses`              | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-before-function-parentheses) |
| `space-in-brackets`                              | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-in-brackets)                 |
| `no-arrow-condition`                             | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-arrow-condition)                |
| `space-after-keywords`                           | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-after-keywords)              |
| `space-before-keywords`                          | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-before-keywords)             |
| `space-return-throw-case`                        | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-return-throw-case)           |
| `no-spaced-func`                                 | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-spaced-func)                    |
| `indent-legacy`                                  | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/indent-legacy)                     |
| `array-bracket-newline`                          | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/array-bracket-newline)             |
| `array-bracket-spacing`                          | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/array-bracket-spacing)             |
| `array-element-newline`                          | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/array-element-newline)             |
| `arrow-parens`                                   | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/arrow-parens)                      |
| `arrow-spacing`                                  | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/arrow-spacing)                     |
| `block-spacing`                                  | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/block-spacing)                     |
| `brace-style`                                    | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/brace-style)                       |
| `comma-dangle`                                   | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/comma-dangle)                      |
| `comma-spacing`                                  | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/comma-spacing)                     |
| `comma-style`                                    | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/comma-style)                       |
| `computed-property-spacing`                      | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/computed-property-spacing)         |
| `dot-location`                                   | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/dot-location)                      |
| `eol-last`                                       | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/eol-last)                          |
| `func-call-spacing`                              | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/func-call-spacing)                 |
| `function-call-argument-newline`                 | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/function-call-argument-newline)    |
| `function-paren-newline`                         | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/function-paren-newline)            |
| `generator-star-spacing`                         | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/generator-star-spacing)            |
| `implicit-arrow-linebreak`                       | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/implicit-arrow-linebreak)          |
| `indent`                                         | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/indent)                            |
| `jsx-quotes`                                     | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/jsx-quotes)                        |
| `key-spacing`                                    | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/key-spacing)                       |
| `keyword-spacing`                                | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/keyword-spacing)                   |
| `linebreak-style`                                | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/linebreak-style)                   |
| `lines-around-comment`                           | 0                                                                   | `undefined undefined` | [Documentation](https://eslint.org/docs/rules/lines-around-comment)              |
| `max-len`                                        | 0                                                                   | `undefined undefined` | [Documentation](https://eslint.org/docs/rules/max-len)                           |
| `max-statements-per-line`                        | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/max-statements-per-line)           |
| `multiline-ternary`                              | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/multiline-ternary)                 |
| `new-parens`                                     | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/new-parens)                        |
| `newline-per-chained-call`                       | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/newline-per-chained-call)          |
| `no-confusing-arrow`                             | 0                                                                   | `undefined undefined` | [Documentation](https://eslint.org/docs/rules/no-confusing-arrow)                |
| `no-extra-parens`                                | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-extra-parens)                   |
| `no-extra-semi`                                  | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-extra-semi)                     |
| `no-floating-decimal`                            | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-floating-decimal)               |
| `no-mixed-operators`                             | 0                                                                   | `undefined undefined` | [Documentation](https://eslint.org/docs/rules/no-mixed-operators)                |
| `no-mixed-spaces-and-tabs`                       | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-mixed-spaces-and-tabs)          |
| `no-multi-spaces`                                | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-multi-spaces)                   |
| `no-multiple-empty-lines`                        | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-multiple-empty-lines)           |
| `no-tabs`                                        | 0                                                                   | `undefined undefined` | [Documentation](https://eslint.org/docs/rules/no-tabs)                           |
| `no-trailing-spaces`                             | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-trailing-spaces)                |
| `no-whitespace-before-property`                  | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/no-whitespace-before-property)     |
| `nonblock-statement-body-position`               | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/nonblock-statement-body-position)  |
| `object-curly-newline`                           | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/object-curly-newline)              |
| `object-curly-spacing`                           | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/object-curly-spacing)              |
| `object-property-newline`                        | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/object-property-newline)           |
| `one-var-declaration-per-line`                   | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/one-var-declaration-per-line)      |
| `operator-linebreak`                             | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/operator-linebreak)                |
| `padded-blocks`                                  | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/padded-blocks)                     |
| `quote-props`                                    | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/quote-props)                       |
| `quotes`                                         | 0                                                                   | `undefined undefined` | [Documentation](https://eslint.org/docs/rules/quotes)                            |
| `rest-spread-spacing`                            | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/rest-spread-spacing)               |
| `semi`                                           | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/semi)                              |
| `semi-spacing`                                   | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/semi-spacing)                      |
| `semi-style`                                     | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/semi-style)                        |
| `space-before-blocks`                            | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-before-blocks)               |
| `space-before-function-paren`                    | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-before-function-paren)       |
| `space-in-parens`                                | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-in-parens)                   |
| `space-infix-ops`                                | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-infix-ops)                   |
| `space-unary-ops`                                | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/space-unary-ops)                   |
| `switch-colon-spacing`                           | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/switch-colon-spacing)              |
| `template-curly-spacing`                         | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/template-curly-spacing)            |
| `template-tag-spacing`                           | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/template-tag-spacing)              |
| `wrap-iife`                                      | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/wrap-iife)                         |
| `wrap-regex`                                     | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/wrap-regex)                        |
| `yield-star-spacing`                             | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/yield-star-spacing)                |
| `react/jsx-space-before-closing`                 | Off                                                                 | `💡 Disabled`         | External rule                                                                    |
| `prettier/prettier`                              | Error                                                               | `🚫 Error`            | External rule                                                                    |
| `arrow-body-style`                               | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/arrow-body-style)                  |
| `prefer-arrow-callback`                          | Off                                                                 | `💡 Disabled`         | [Documentation](https://eslint.org/docs/rules/prefer-arrow-callback)             |
<!--END_SECTION:eslint-->

---

## 📝 [`@blackzacktech/renovate-config`](/packages/renovate-config/)

> [!WARNING]
> This is not a package - it is a configuration preset!

### 🔩 Usage
In your `renovate.json` file, add the following:
```json
{
 "extends": ["github>blackzacktech/shared-configs//packages/renovate-config/index.json"]
}
```
