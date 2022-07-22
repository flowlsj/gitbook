# eth\_protocolVersion

Returns the current Ethereum protocol version.

**Parameters**

None

**Returns**

`String` - The current Ethereum protocol version

**Example**

```js
// Request
curl -X POST --data '{"jsonrpc":"2.0","method":"eth_protocolVersion","params":[],"id":67}'
// Result
{
  "id":67,
  "jsonrpc": "2.0",
  "result": "54"
}
```
