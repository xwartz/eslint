# ESLint Config

This is personal eslint configuration.

## Usage

### JavaScript
- Install

```bash
pnpm i -D @xwartz/eslint-config
```

- Add config to `.eslintrc`:

```
{
  "extends": "@xwartz/eslint-config"
}
```

### TypeScript

- Install

```bash
pnpm i -D @xwartz/eslint-config-ts
```

- Add config to `.eslintrc`:

```
{
  "extends": ["@xwartz/eslint-config-ts"],
  "parserOptions": {
    "project": "./tsconfig.json"
  }
}
```

#### React

- Install

```bash
pnpm i -D @xwartz/eslint-config-react @xwartz/eslint-config-ts
```

- Add config to `.eslintrc`:

```
{
  "extends": ["@xwartz/eslint-config-ts", "@xwartz/eslint-config-react"],
  "parserOptions": {
    "project": "./tsconfig.json"
  }
}
```


## Prettier

- Install

```bash
pnpm i -D @xwartz/prettier
```

- Add config to `package.json`

```
{
  "prettier": "@xwartz/prettier"
}
```
