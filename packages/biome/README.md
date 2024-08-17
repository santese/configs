# @santese/biome-config

Shareable Biome configuration

## Description

This package provides a shareable configuration for Biome, a performant
formatter, linter, and more for JavaScript, TypeScript, and JSON.

## Installation

You can install this package using pnpm, yarn, or npm:

### pnpm

```bash
pnpm i -D @santese/biome-config
```

### npm

```bash
npm install -D @santese/biome-config
```

### yarn

```bash
yarn add -D @santese/biome-config
```

## Usage

After installing the package, you can use it in your Biome configuration file.
Create a `biome.json` file in your project root and extend this configuration:

```json
{
    "extends": ["@santese/biome-config"]
}
```

## Configuration

The main configuration file is `biome.jsonc`. You can find it in the root of
this package.

## License

This project is licensed under the MIT License.

## Issues

If you encounter any issues or have suggestions, please file them in the
[issues section](https://github.com/github.com/santese/configs/issues) of the
repository.

## Author

@santese

## Repository

This package is part of the
[santese/configs](https://github.com/santese/configs) monorepo, located in the
`packages/biome` directory.
