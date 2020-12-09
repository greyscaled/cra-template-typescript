# @vapurrmaid/cra-template-typescript

[@vapurrmaid](https://github.com/vapurrmaid)'s opinionated TypeScript React
setup

## Project Structure

The shell project placed a `.gitkeep` placeholder in each of the following:

- `components/`:
  - Reusable components
- `contexts/`
  - `React.Context`s (global, or higher-level scope)
- `entities/`
  - Domain logic
- `pages/`
  - Complete views built from components etc. May contain localized components,
    contexts, hooks
- `utils/`
  - Language/library extensions

These aren't the only forseeable organizational units. For example `services` or
`api` may be another commonly used directory.

## Stack

- TypeScript
- React
- TypeStyle

## Tooling

- `@vapurrmaid/prettier-config`
  [source](https://www.npmjs.com/package/@vapurrmaid/prettier-config)
- `@typescript-eslint`, configured with the following
  [source](https://github.com/vapurrmaid/cra-template-typescript/blob/master/template/.eslintrc):
  - `eslint:recommended`
  - `plugin:@typescript-eslint/recommended`
  - `plugin:react/recommended`
  - `plugin:react-hooks/recommended`
