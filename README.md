![KAPU Explorer](https://github.com/gsilvestri/kapu-explorer/blob/master/KAPU_EXPLORER.jpg)

[![Build Status](https://img.shields.io/travis/gsilvestri/kapu-explorer/master.svg?style=flat)](https://travis-ci.org/gsilvestri/kapu-explorer)

# KAPU Explorer 3.0

> Designed and developed from the ground-up, using lean & fast developmental frameworks (Tailwind CSS & Vue.JS).

You can access it at [https://explorer.kapunode.net/](https://explorer.kapunode.net/).

## Build Setup

### 1. Clone the repository

```bash
git clone https://github.com/gsilvestri/kapu-explorer
```

### 2. Install Dependencies

```bash
yarn install
```

### 3. Build for Production

#### 3.1 Mainnet

```bash
yarn build:mainnet
```

#### 3.2 Devnet

```bash
yarn build:devnet
```

#### 3.3 Custom

```bash
yarn build --network my-custom-network
```

#### 3.4 GitHub Pages

If you are going to host your explorer instance on GitHub Pages you will need to specify your base url in most cases as GitHub Pages serves repositories from sub-directories instead of sub-domains.

```bash
yarn build --base https://username.github.io/repository/
```

A running instance of the explorer on GitHub Pages can be found at https://gsilvestri.github.io/.

> This step is not required if you are hosting the explorer on your "root" repository which is usually your username https://username.github.io/.

## 4. History Mode

If you wish to remove the `/#/` from your URLs you can follow those steps https://router.vuejs.org/en/essentials/history-mode.html.

> Keep in mind that this requires you to run your own server and a running instance of nginx.

## 5. Development

#### Mainnet

```bash
yarn dev # or yarn dev:mainnet
```

#### Devnet

```bash
yarn dev:devnet
```

#### Custom

```bash
EXP_NETWORK=custom yarn dev
```

#### Change Router Mode

```bash
EXP_ROUTER=history yarn dev
```

## 6. Testing

``` bash
$ yarn test
```

## 7. Security

If you discover a security vulnerability within this package, please send an e-mail to security@kapu.one. All security vulnerabilities will be promptly addressed.

## 8. Credits

- [Brian Faust](https://github.com/faustbrian)
- [Lúcio Rubens](https://github.com/luciorubeens)
- [Alex Barnsley](https://github.com/alexbarnsley)
- [Giovanni Silvestri](https://github.com/gsilvestri)
- [All Contributors](../../contributors)

## 9. License

[MIT](LICENSE) © [KAPU International](https://kapu.one)
