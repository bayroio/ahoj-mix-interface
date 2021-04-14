# Ahoj.Mix Interface

An open source interface for Ahoj.Mix, a DEX digital assets, powered by Avalanche.

- Website: [ahoj.finance](https://www.ahoj.finance/)
- Interface: [mix.ahoj.finance](https://mix.ahoj.finance/)
- Twitter: [@bayro_io](https://twitter.com/bayro_io)


## Accessing the Ahoj.Mix Interface

Visit [mix.ahoj.finance](https://mix.ahoj.finance/).

## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to your JSON-RPC provider 

Note that the interface only works on testnets where both 
[Ahoj.Mix V1](https://github.com/bayroio/ahoj-mix-v1-contracts) and 
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Attribution
This code was adapted from this Uniswap repo [uniswap-interface](https://github.com/Uniswap/uniswap-interface) and interface for Pangolin repo [interface](https://github.com/pangolindex/interface).
