# Kin Node SDK Demo


## This app demonstrates how to integrate with [Kin](https://developer.kin.org/) via the [Node SDK](https://github.com/kinecosystem/kin-node)



## Front End
This Kin BE Demo Server is compatible with our [Kin SDK Front End](https://github.com/kin-labs/kin-demo-web-sdk-and-server-fe)

## Prep
- Your App is registered on the [Kin Developer Portal](https://portal.kin.org/) so you can take advantage of the [Kin Rewards Engine](https://developer.kin.org/docs/the-kre-explained/) and get your App Index
- Environment variable for your App Index
- Environment variable for your Private Key. Visit [The Kin Laboratory](https://laboratory.kin.org/home) if you want help getting started with Keypairs for testing
- Environment variable for your Webhook Secret (if using webhooks)

`.env`

```
APP_INDEX=Your App App Index
PRIVATE_KEY=Your App Account Secret Key
SERVER_WEBHOOK_SECRET=Your Webhook Secret
```
## Install Packages - Make sure you're using Node 12

```
npm i
```

or

```
yarn
```
## Start

```
npm run start
```

or

```
yarn start
```
## If you're just getting started, you might want to look at [this](https://developer.kin.org/tutorials/#getting-started) first...

## Dev Community
Join us on [Discord](https://discord.com/invite/kdRyUNmHDn) if you're looking for support with your App or to connect with other active Kin developers.

If you're stuck or have any questions you'd like answering, get in touch on our [kin-node](https://discord.com/channels/808859554997469244/811117045742960640) channel.