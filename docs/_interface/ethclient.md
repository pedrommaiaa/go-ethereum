# Ethclient

The ethclient package provides a RPC client for the Ethereum RPC API. 

To work with this package you first need to be connected to an Ethereum 
node, this can be done using your own node or any Ethereum client service 
provider. 

```Go
package main

import (
    "log"

    "github.com/ethereum/go-ethereum/ethclient"
)

function main() {
    client, err := ethclient.Dial("http://localhost:8545")
    if err != nil {
        log.Fatal(err)
    }

    // Now you're connected to the Ethereum network!
}
```

## Client

## Blockchain Access

## State Access

## Filters

## Pending State

## Contract Calling
