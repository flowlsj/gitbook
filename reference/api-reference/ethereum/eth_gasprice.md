# eth\_gasPrice

Returns the current price per gas in wei.

**Parameters**

None

**Returns**

`QUANTITY` - integer of the current gas price in wei.

**Example**

```js
// Request
curl -X POST --data '{"jsonrpc":"2.0","method":"eth_gasPrice","params":[],"id":73}'
// Result
{
  "id":73,
  "jsonrpc": "2.0",
  "result": "0x1dfd14000" // 8049999872 Wei
}
```
