1. Swap our ETH for WETH
2. Deposit some ETH (WETH) into Aave
3. Borrow some asset with the ETH collateral
    1. Sell that borrowed asset. (Short sell)
4. Repay everything back


Testing:

Integration test: Kovan

Unit tests: Mainnet-fork (Since we are not using oracles hence no need of mocks)
