# eth\_newBlockFilter

Creates a filter in the node, to notify when a new block arrives. To check if the state has changed, call [eth\_getFilterChanges](eth\_getfilterchanges.md).

**Parameters** None

**Returns** `QUANTITY` - A filter id.

**Example**

```js
// Request
curl -X POST --data '{"jsonrpc":"2.0","method":"eth_newBlockFilter","params":[],"id":73}'
// Result
{
  "id":1,
  "jsonrpc":  "2.0",
  "result": "0x1" // 1
}
```
