# Liquidation-Data-Inspection
Liquidation Data Inspection on a DeFi application

On 16.07.2025, some of the users from a DeFi application called "Malda.xyz" got liquidated.

The incident took place between block 20061813 and block 20061910 of the Linea network.
  
This incident affected users who utilize weETH market.

The liquidations happened with the following specific method: "Fulfill Basic Order_efficient_6GL6yc"

In this repo, we will follow these steps:

- Find the contract address of weETH market of Malda
- Download the underlying transactions as a csv file
- Import data to a python workbook and import Pandas library
- Filter the dataset based on the specific method given above to confirm the block number range is correct
- Create a sub dataset of affected user wallets by displaying outstanding supply-borrow positions at the time of the incident
