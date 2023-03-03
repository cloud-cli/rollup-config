# Rollup shared configuration

Usage:

```
npm i -D @cloud-cli/rollup-config
```

`rollup.config.js`:
```js
import defaults from '@cloud-cli/rollup-config'

export default {
  ...defaults,
  // add overrides if needed:
  external: ['rxjs'],
};
```