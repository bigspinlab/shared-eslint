# Bigspin Lab ESLint Config

This is an opionated configuration preset for ESLint, tailored
for Bigspin Lab JavaScript/TypeScript projects.

## Setting up

1. Install:

```bash
$ npm i --save-dev @bigspinlab/shared-eslint

# Install peer dependencies
$ npx install-peerdeps --dev @bigspinlab/shared-eslint
```

2. Add the following to `package.json`:

```json
{
  "eslintConfig": {
    "extends": [
      "@bigspinlab/shared-eslint"
    ]
  }
}
```

Or, `touch .eslintrc` file and add:

```json
{
  "extends": [
    "@bigspinlab/shared-eslint"
  ]
}
```
