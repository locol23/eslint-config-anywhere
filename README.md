# eslint-config-everywhere・[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

ESLint config for everywhere

# Installation

```
yarn add -D eslint eslint-config-everywhere
```

# Usage

In your ESLint config file, set the `extends` property:

## Configure

### Base

```js
{
  "extends": "everywhere"
}
```

### React

```js
{
  "extends": ["everywhere", "everywhere/react"]
}
```

### TypeScript

```json
{
  "extends": ["everywhere", "everywhere/typescript"]
}
```

### React + TypeScript

```json
{
  "extends": [
    "everywhere",
    "everywhere/react",
    "everywhere/typescript"
  ]
}
```

### Test(Jest + testing-library/react + Playwright)

```json
{
  "extends": ["everywhere/jest", "everywhere/testing-library-react", "everywhere/playwright"]
}
```

### Storybook

```json
{
  "extends": ["everywhere/storybook"]
}
```

### All

```json
{
  "extends": [
    "everywhere",
    "everywhere/react",
    "everywhere/typescript",
    "everywhere/jest",
    "everywhere/testing-library-react",
    "everywhere/playwright",
    "everywhere/storybook"
  ]
}
```

## Run ESLint

```sh
eslint /path/to/your_source
```

# Lisence

[MIT](LICENSE)
