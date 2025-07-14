# Liquidation-Data-Inspection
Liquidation Data Inspection on a DeFi application

On 16.07.2025, some of the users from a DeFi application called "Malda.xyz" got liquidated due to an error on the oracle side.

The incident took place between block 20061813 and block 20061910 of the Linea network.

The involved liquidators are:
  0xe127ec89f68ec01e5dbc5ef896def830a9ab187e
  0x6cf846518e2b8971e48865d4b43b18513417a2b5
  0x7f07927ba39e0f85a7c21fd36ae08bfd99cad993
  0x8e595231305efc7ef256679ad95847cb255ef846
  0x66675110f43bd6469c5ceed5cc739ed8472e6d79
  0x5b74ac8f848f19f102b52e2e18448fef70e51f7e
  
This incident affected users who utilize weETH market.

The liquidations happened with the following specific method: "Fulfill Basic Order_efficient_6GL6yc"

In this repo, we will follow these steps:

- Find the contract address of weETH market of Malda
- Download the underlying transactions as a csv file
- Import data to a python workbook and import Pandas library
- Filter the dataset based on the specific method given above to confirm the block number range is correct
- Create a sub dataset of affected user wallets by displaying outstanding supply-borrow positions at the time of the incident
