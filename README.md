# PuffySwap SDK

This repository has been forked from [UniswapV2](https://github.com/Uniswap/uniswap-sdk)

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/QuickSwap/QuickSwap-sdk.git //changbhkhk\
```

Move into the quickswap-sdk working directory

```sh
cd QuickSwap-sdk/

entities/currency - set native currency
entities.pair - set this -
      'PUF',
      'Puffyswap'
entities/token - set WETH   
constant - set chainids, set factory, set init code hash
fetcher - set tokens decimal cache  
```

Install dependencies

```sh
npm i puffyswap-sdk
install from npm for dapp usage


```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
#� �P�u�f�f�y�S�w�a�p�-�s�d�k�
�
�
