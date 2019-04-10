# u-chain

A tiny implementation of a blockchain, for educational purposes. Inspired by [snakecoin](https://gist.github.com/aunyks/47d157f8bc7d1829a729c2a6a919c173).

### Usage

Create a transaction.

```
curl "localhost:5000/txion" \
     -H "Content-Type: application/json" \
     -d '{"from": "foo", "to":"bar", "amount": 3}'
```

Mine a new block.

```
curl localhost:5000/mine
```
