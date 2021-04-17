# Ethereum Full Node (Mainnet and Testnet)

### Startup

```
docker-compose up -d
```

## Check sync status

```
docker exec ethereum_mainnet geth attach http://127.0.0.1:8545 --exec eth.syncing
```


## Check logs

```
docker logs ethereum_mainnet --tail 10 --follow
```
