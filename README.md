# Osu! Utility

A browser extension meant to help the player

- [Osu! Utility](#osu-utility)
  - [Build](#build)
    - [Install dependencies](#install-dependencies)
    - [Run Development](#run-development)
  - [Production build](#production-build)

## Build

### Install dependencies

```bash
pnpm install
```

### Run Development

```bash
pnpm dev
```

Then **load extension in browser with the `extension/` folder**.

For Firefox developers, you can run the following command instead:

```bash
pnpm start:firefox
```

`web-ext` auto reload the extension when `extension/` files changed.

> While Vite handles HMR automatically in the most of the case, [Extensions Reloader](https://chrome.google.com/webstore/detail/fimgfedafeadlieiabdeeaodndnlbhid) is still recommanded for cleaner hard reloading.

## Production build

To build the extension, run

```bash
pnpm build
```

And then pack files under `extension`, you can upload `extension.crx` or `extension.xpi` to appropriate extension store.

<br /><br />

<!-- ![<https://github.com/GaussianWonder/osu-utility/>](./extension/assets/repo_qr.png?sanitize=true "https://github.com/GaussianWonder/osu-utility") -->

<p align="center">
<sub>Share QR</sub><br />
<img src="./extension/assets/repo_qr.png" width="128px" height="128px" /><br />
<sub>
<sub><b>QR URL:</b></sub><br />
<sub>https://raw.githubusercontent.com/GaussianWonder/osu-utility/main/extension/assets/repo_qr.png</sub><br />
</sub>
</p>
