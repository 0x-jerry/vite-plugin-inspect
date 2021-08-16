# vite-plugin-inspect

[![NPM version](https://img.shields.io/npm/v/vite-plugin-inspect?color=a1b858&label=)](https://www.npmjs.com/package/vite-plugin-inspect)

{**WIP**} Inspect the intermediate state of Vite plugins

![image](https://user-images.githubusercontent.com/11247099/129511471-8d040306-31fc-45b5-9a91-508f995c8658.png)

## Install

```bash
npm i -D vite-plugin-inspect
```

Add plugin to your `vite.config.ts`:

```ts
// vite.config.ts
import Inspect from 'vite-plugin-inspect'

export default {
  plugins: [
    Inspect()
  ]
}
```

Then visit [localhost:3000/__inspect](http://localhost:3000/__inspect) to inspect the modules.

## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/antfu/static/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/antfu/static/sponsors.svg'/>
  </a>
</p>

## License

[MIT](./LICENSE) License © 2021 [Anthony Fu](https://github.com/antfu)
