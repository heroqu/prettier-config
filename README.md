# `@heroqu/prettier-config`

Personal [Prettier](https://prettier.io) config.

## Usage

**Install**:

```bash
$ yarn add --dev @heroqu/prettier-config
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@heroqu/prettier-config"
}
```

### Overriding...

If one would like to override some settings one can instead import the file in a `.prettierrc.js` file and export the modifications, e.g.:

```javascript
module.exports = {
  ...require("@heroqu/prettier-config"),
  semi: false,
};
```
