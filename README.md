# unplugin-triple-slash-derective

## Install

```sh
npm i unplugin-triple-slash-derective
```

<details>
<summary>esbuild</summary><br>

```js
// esbuild.config.js
import { build } from 'esbuild'
import { UnpluginTripleSlashDerectivePlugin } from 'unplugin-triple-slash-derective/esbuild'

build({
  plugins: [
    UnpluginTripleSlashDerectivePlugin(/* options */)
  ],
})
```

<br></details>

<details>
<summary>Rollup</summary><br>

```js
// rollup.config.js
import { UnpluginTripleSlashDerectivePlugin } from 'unplugin-triple-slash-derective/rollup'

export default {
  plugins: [
    UnpluginTripleSlashDerectivePlugin(/* options */)
  ],
}
```

<br></details>

<details>
<summary>Vite</summary><br>

```js
// vite.config.ts
import { UnpluginTripleSlashDerectivePlugin } from 'unplugin-triple-slash-derective/vite'

export default defineConfig({
  plugins: [
    UnpluginTripleSlashDerectivePlugin(/* options */)
  ],
})
```

<br></details>

<details>
<summary>Webpack</summary><br>

```js
// webpack.config.js
const { UnpluginTripleSlashDerectivePlugin } = require('unplugin-triple-slash-derective/webpack');

module.exports = {
  plugins: [
    UnpluginTripleSlashDerectivePlugin(/* options */),
  ],
};
```

<br></details>
