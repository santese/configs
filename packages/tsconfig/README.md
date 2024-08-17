# @santese/tsconfig

Shared TypeScript configurations

## Description

This package provides shared TypeScript configurations for various project types. It includes base configurations as well as specialized configurations for Bun and library projects.

## Installation

You can install this package using pnpm, npm, or yarn:


### pnpm

```bash
pnpm add -D @santese/tsconfig
```


### npm

```bash
npm install -D @santese/tsconfig
```

### yarn

```bash
yarn add -D @santese/tsconfig
```

## Usage

After installing the package, you can use it in your `tsconfig.json` file. Extend the configuration you need:

### Base Configuration

```json
{
  "extends": "@santese/tsconfig"
}
```

### Bun Configuration

```json
{
  "extends": "@santese/tsconfig/bun"
}
```

### Library Configuration

```json
{
  "extends": "@santese/tsconfig/lib"
}
```

## Configurations

This package includes the following configurations:

- `base.json`: The base TypeScript configuration
- `bun.json`: Configuration optimized for Bun projects
- `lib.json`: Configuration for library projects

## License

This project is licensed under the MIT License.

## Issues

If you encounter any issues or have suggestions, please file them in the [issues section](https://github.com/github.com/santese/configs/issues) of the repository.

## Author

@santese

## Repository

This package is part of the [santese/configs](https://github.com/santese/configs) monorepo, located in the `packages/tsconfig` directory.