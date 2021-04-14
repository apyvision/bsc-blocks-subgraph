## Deployment APY VISION
```
nvm use 10.16.3
```

To generate the mapping ts files, please do:
```
yarn codegen
```

To deploy, please use:
```
graph deploy \
    --debug \
    --node https://api.thegraph.com/deploy/ \
    --ipfs https://api.thegraph.com/ipfs/ \
    apyvision/block-info
```
