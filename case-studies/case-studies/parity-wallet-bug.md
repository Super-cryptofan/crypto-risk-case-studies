# Parity Wallet Bug
Category: Smart Contract Failure  
Year: 2017
Overview:
A critical bug in the Parity multi-signature wallet library caused a large amount of Ether to become permanently locked.
## Library Contract Design
The Parity wallet relied on a shared library contract used by many deployed wallets.
## Accidental Trigger
A user accidentally triggered a function that disabled the wallet library contract.
## Frozen Funds
Because the library contract was disabled, many wallets lost the ability to access their funds.
