# @aboutbits/ts-config

[![npm package](https://badge.fury.io/js/%40aboutbits%2Fts-config.svg)](https://badge.fury.io/js/%40aboutbits%2Fts-config)
[![license](https://img.shields.io/github/license/aboutbits/ts-config)](https://github.com/aboutbits/ts-config/blob/main/license.md)

AboutBit's [ESLint](https://eslint.org/) config presets

## Usage

Install the package, assuming that you have TypeScript already installed:

```sh
npm i -D @aboutbits/ts-config
```

### For TypeScript without React

`tsconfig.json`

```json
{
  "extends": "@aboutbits/ts-config"
}
```

### For TypeScript with React

`tsconfig.json`

```json
{
  "extends": "@aboutbits/ts-config/react"
}
```

## Publish

To publish the package commit all changes and push them to main. Then run one of the following commands locally:

```sh
npm version patch
npm version minor
npm version major
```

## Information

AboutBits is a company based in South Tyrol, Italy. You can find more information about us
on [our website](https://aboutbits.it).

### Support

For support, please contact [info@aboutbits.it](mailto:info@aboutbits.it).

### Credits

- [All Contributors](../../contributors)

### License

The MIT License (MIT). Please see the [license file](license.md) for more information.
