# Documentation and information about Sense.Chat and the SENSE token.

## If you want to teleport your SENSE ERC-20 tokens to SENSE EOS-21 tokens, then load your ethereum account into metamask and follow this simple site we built. https://sensetoken.com

## Instructions for manual token teleportation
1. Read your token balance (total ERC-20 balance i.e. 23 SENSE = 2300000000)
2. Call `approve` function with the amount as 2300000000 and address as the migration contract address.
3. Once that reaches 6 confirmations...
4. Then we can teleport the tokens by sending the EOS account to the Teleport actioncall `Teleport` function with your EOS account name (12 letters).
5. Wait for 6 confirmations and verify that your EOS balance of SENSE tokens has been updated appropriately.

##  ETH addresses:

`teleportation ETH contract address: 0x53e79ec852399f7306F8Cc94D424d60688c02C61`

`SENSE ERC-20 token contract address: 0x6745fAB6801e376cD24F03572B9C9B0D4EdDDCcf`
