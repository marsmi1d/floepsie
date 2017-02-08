# readme

```json
{
  "nonce": "0x0000000000000042",
    "mixhash": "0x0000000000000000000000000000000000000000000000000000000000000000",
    "difficulty": "0x4000",
    "alloc": {},
    "coinbase": "0x0000000000000000000000000000000000000000",
    "timestamp": "0x00",
    "parentHash": "0x0000000000000000000000000000000000000000000000000000000000000000",
    "extraData": "Custem Ethereum Genesis Block",
    "gasLimit": "0xffffffff"
}
```


geth --networkid 123 --datadir ./nodes/test init genesis.json

geth --datadir ./nodes/test/ --networkid 123 --nodiscover --maxpeers 0 console

>personal.newAccount("floepie");
"0x0499a04579f7f24ae71d0c6322350937b6372877"

