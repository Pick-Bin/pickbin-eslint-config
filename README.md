# pcikbin-eslint-config

Pickbin-flavored ESLint config.

## Installation

```sh
$ npm install eslint pickbin-eslint-config --save-dev
```

## Usage

Create an `.eslintrc.yml` file with the following:

```yaml
extends: pickbin-eslint-config
```

Add the following `script` to your `package.json`:

```json
{
  "scripts": {
    "lint": "eslint ."
  }
}
```

and run the linter with:

```sh
$ npm run lint
```
