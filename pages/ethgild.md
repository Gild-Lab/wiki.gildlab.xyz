- [[ethgild/why/gild]]
- [[ethgild/why/buy]]
- [[ethgild/how/price]]
- Gild: to cover with gold.
  A hybrid erc20 and erc1155 that mints/burns at a reference gold price from Chainlink oracles, denominated in ETH.
  The erc20 is called `EthGild` with symbol `ETHg`. It works much like wrapping/unwrapping `ETH` to `WETH`.
  Send ETH to the payable `gild` function to gild it and receive ETHg erc20 and erc1155 in equal amounts at current reference gold price.
  Call `ungild` to burn 100.1% erc20 against any erc1155 to ungild the ETH that was created against that erc1155.
  Trade either the erc20 and/or the erc1155 on any markets that support those standards.