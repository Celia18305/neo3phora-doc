## GetAssetInfoByContractHash

Gets the asset information with the contract script hash.

### Parameters

| Name         | Type   | Description |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract script hash |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"ContractHash":"0xd2a4cff31913016155e38e474a2c06d08be276cf"},
    "method": "GetAssetInfoByContractHash"
}'
```

### Output

// TODO

