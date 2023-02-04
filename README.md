# Token Boyz 🤑💲

### Get all tokens from a wallet address 💸

- Create a `.env` file with the following content:

```bash
API_KEY="YOUR_ALCHEMY_API_KEY"
```

- The available networks are:

```js
// available mainnet networks are:
const myNetworks = [
	Network.OPT_MAINNET,
	Network.ARB_MAINNET,
	Network.ETH_MAINNET,
	Network.MATIC_MAINNET,
];
```

- To run the program:

```bash
node main.js
```

- To get native tokens, we can use `wagmi`.🚀🔥

---

## Some interesting APIS 🥳

#### Medium blog url:
 https://towardsdatascience.com/obtaining-historical-and-real-time-crypto-data-with-very-simple-web-programming-7b481f153630 

- API to get current price of a token:

```sh
https://min-api.cryptocompare.com/data/price?fsym=USDC&tsyms=INR
```

- API to get historical price of a token:

```sh
https://min-api.cryptocompare.com/data/v2/histohour?fsym=ETH&tsym=USD&limit=2000&toTs=-1&api_key=YOURKEYHERE
```

# ================== 🤑 ==================