# NinjaCoin Wallet Pro Wallet

![Download Count](https://img.shields.io/github/downloads/ninjacoin-master/ninja-wallet-pro/total.svg)
![Open Issue Count](https://img.shields.io/github/issues/ninjacoin-master/ninja-wallet-pro)
![License](https://img.shields.io/github/license/ninjacoin-master/ninja-wallet-pro)
![Version](https://img.shields.io/github/v/release/ninjacoin-master/ninja-wallet-pro)

### Master Build Status

![Master Build Status](https://github.com/ninjacoin-master/ninja-wallet-pro/workflows/Build%20NinjaCoin Wallet Pro/badge.svg?branch=master)

### Development Build Status

![Development Build Status](https://github.com/ninjacoin-master/ninja-wallet-pro/workflows/Build%20NinjaCoin Wallet Pro/badge.svg?branch=development)

<img src="https://raw.githubusercontent.com/ninjacoin-master/ninja-wallet-pro/development/screenshots/screenshot.png">
<p>
  NinjaCoin Wallet Pro Wallet is a NinjaCoin wallet that uses <a href="http://electron.atom.io/">Electron</a>, <a href="https://facebook.github.io/react/">React</a>, <a href="https://github.com/turtlecoin/ninjacoin-wallet-backend-js">Turtlecoin-Wallet-Backend-JS</a>, <a href="https://github.com/reactjs/redux">Redux</a>, <a href="https://github.com/reactjs/react-router">React Router</a>, <a href="http://webpack.github.io/docs/">Webpack</a> and <a href="https://github.com/gaearon/react-hot-loader">React Hot Loader</a>.
</p>

<p>
  All of the code is released under the GPLv3 license. The icons in the ./resources and ./app/images folders, however, are not released under this license, rather they are maintained to be intellectual property of ExtraHash, and may not be used to represent the brand or identity of any other piece of software or group. See the included license file in ./resources/LICENSE and ./app/images/LICENSE for more details.
</p>

## Installing

**Check out the full tutorial on how to install and use NinjaCoin Wallet Pro at the [official NinjaCoin docs page](https://docs.turtlecoin.lol/guides/wallets/using-ninja-wallet-pro)!**

## Development Setup (All Platforms)

### Dependencies

#### You will need the following dependencies installed before you can proceed to the "Setup" step:

- Node.JS (Latest LTS version - 10.x) https://nodejs.org/

- Yarn https://yarnpkg.com/en/

- Git https://git-scm.com/downloads

Tip: If you already have a different version of node.js installed besides 10.x, try using [Node Version Manager](https://github.com/nvm-sh/nvm#install--update-script).

#### Setup

First, clone the repo via git:

```bash
git clone https://github.com/ninjacoin-master/ninja-wallet-pro.git
```

And then install the dependencies with yarn.

```bash
$ cd ninja-wallet-pro
$ yarn
```

Run the wallet.

```bash
$ yarn start
```

### Starting Development

Start the app in the `dev` environment. This starts the renderer process in [**hot-module-replacement**](https://webpack.js.org/guides/hmr-react/) mode and starts a webpack dev server that sends hot updates to the renderer process:

```bash
$ yarn dev
```

### Packaging

To package apps for the local platform:

```bash
$ yarn package
```

## License

© [ExtraHash](https://github.com/ExtraHash)
See included License file for more details.
