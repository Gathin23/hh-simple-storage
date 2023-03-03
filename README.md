## Quickstart

Contract Deployed to in Goerli:
```
0xe9dfa2241e7622bb50caDB64DB2d5a048531248A
```

```
git clone https://github.com/Gathin23/hh-simple-storage.git
cd hardhat-simple-storage-fcc
yarn
yarn hardhat
```

## Typescript

For the typescript edition, run:

```
git checkout typescript
```


# Usage

Deploy:

```
npx hardhat run scripts/deploy.js
```

## Testing

```
npx hardhat test
```

### Test Coverage

```
npx hardhat coverage
```

## Estimate gas

You can estimate how much gas things cost by running:

```
npx hardhat test
```

And you'll see and output file called `gas-report.txt`

## Local Deployment 

If you'd like to run your own local hardhat network, you can run:

```
npx hardhat node
```

And then **in a different terminal**

```
npx hardhat run scripts/deploy.js --network localhost
```