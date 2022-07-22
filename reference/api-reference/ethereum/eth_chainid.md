# eth\_chainId

Returns the currently configured chain ID, a value used in replay-protected transaction signing as introduced by EIP-155.

**Parameters**

None

**Returns**

`QUANTITY` - integer of the current chain ID.

**Example**

```js
// Request
curl -X POST --data '{"jsonrpc":"2.0","method":"eth_chainId","params":[],"id":73}'
// Result
{
  "id": 73,
  "jsonrpc": "2.0",
  "result": "0x3d" // 61
}
```
