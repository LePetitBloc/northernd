# FAQ

## The `masternode outputs` return an empty object.
```
{
}
```

You must receive the **1000 NORT** for the **masternode** in a single transaction on your **Control Wallet** and wait for at least 1 confirmation.
> If you already have the **1000 NORT** but it came from multiple transactions, you can send the **1000 NORT** back to yourself:
```
docker exec northern-wallet northern-cli sendfrom "" YoUrAdDr3Ss NORT
```

## Running a **wallet** or a **masternode** container result in the following error:
```
No such file or directory
```

Ensure the `data` folder is *writable* for the container.
