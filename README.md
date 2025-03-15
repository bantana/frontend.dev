# README

## ENV

```bash env install
bun create vite frontend.dev --template vanilla
cd frontend.dev
ncu -u
bun add -D vite-plugin-oxlint oxlint
```

```js vite.config.js

import oxlintPlugin from "vite-plugin-oxlint";

export default {
  plugins: [oxlintPlugin()],
};

```

```bash run dev
bunx --bun vite
```
