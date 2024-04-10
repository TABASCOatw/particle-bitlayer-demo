<div align="center">
  <a href="https://particle.network/">
    <img src="https://i.imgur.com/P391e8h.png" />
  </a>
  <h3>
    Particle Network BTC Connect Bitlayer Demo
  </h3>
</div>

⚡️ Demo application showcasing the implementation of Particle Network's BTC Connect product on Bitlayer, the first Bitcoin security-equivalent L2 based on BitVM. This demo onboards a user through a Bitcoin-native wallet (such as UniSat, OKX, TokenPocket, Bybit, or Bitget), assigns a smart account (on Bitlayer), and executes a gasless burn transaction.

Built using **BTC Connect (by Particle Network)**, **TypeScript**

## ₿ BTC Connect
BTC Connect takes advantage of ERC-4337 alongside (Bitcoin) Layer-2 EVM-compatible blockchains to leverage a Smart Account, Paymaster, Bundler natively within Bitcoin wallets (connected to through a Bitcoin-specific modal also provided by BTC Connect). As its core, BTC Connect enables existing BTC wallets to control smart accounts on Layer-2s.

![](https://i.imgur.com/6V4dAgo.png)

##

👉 Try the demo: https://btc-connect-demo.particle.network

👉 Learn more about Particle Network: https://particle.network

## 🛠️ Quickstart

### Clone this repository
```
git clone https://github.com/TABASCOatw/particle-bitlayer-demo.git
```

### Install dependencies
```
yarn install
```
OR
```
npm install
```

### Set environment variables
This project requires a number of keys from Particle Network to be defined in `.env`. The following should be defined:
- `REACT_APP_APP_ID`, the ID of the corresponding application in your [Particle Network dashboard](https://dashboard.particle.network/#/applications).
- `REACT_APP_PROJECT_ID`, the ID of the corresponding project in your [Particle Network dashboard](https://dashboard.particle.network/#/applications).
-  `REACT_APP_CLIENT_KEY`, the client key of the corresponding project in your [Particle Network dashboard](https://dashboard.particle.network/#/applications).

### Start the project
```
npm run dev
```
OR
```
yarn dev
```
