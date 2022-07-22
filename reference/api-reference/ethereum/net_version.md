# net\_version

Returns the current network id.

**Parameters**

None

**Returns**

`String` - The current network id.

The full list of current network IDs is available at [chainlist.org](https://chainlist.org). Sopme common ones are: `1`: Ethereum Mainnet `2`: Morden testnet (now deprecated) `3`: Ropsten testnet `4`: Rinkeby testnet `5`: Goerli testnet

**Example**

```js
// Request
curl -X POST --data '{"jsonrpc":"2.0","method":"net_version","params":[],"id":67}'
// Result
{
  "id":67,
  "jsonrpc": "2.0",
  "result": "3"
}
```
