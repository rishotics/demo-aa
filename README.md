# Create Custom SCW

### Intall Dependency

```shell
yarn
```

### Prepack the contracts
This compiles the SCW & places the types in `src/` folder

```shell
yarn prepack
```

### Run the runOp file to test the SCW

```shell
INFURA_ID=<infura-id> MNEMONIC_FILE=<file-containing-private-key> yarn runop --network goerli
```
