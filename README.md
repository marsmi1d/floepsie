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

geth --datadir ./nodes/test/ --networkid 123 --nodiscover --maxpeers 0 console
>personal.newAccount("floepie");
"0x0499a04579f7f24ae71d0c6322350937b6372877"

Node 1: geth --genesis genesis.json --networkid 123 --datadir ./nodes/test -port 30301 --rpcport 8101 console
Node 2: geth --genesis genesis.json --networkid 123 --datadir ./nodes/test -port 30302 --rpcport 8102 console

admin.addpeer("enode://4254bdedbda2be4dbbc2502d2e1dd69a186390316522ed6fb4991db9955efdaaa6f04308ad7ff64e40b78954d5e9fe69de000b7f9cc2a1915ba9386c6d6edf78@<ip-adres>:30302")
