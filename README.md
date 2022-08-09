# Welcome to the Connected Cross Chain Future Workshop
![Banner Image](https://img.evbuc.com/https%3A%2F%2Fcdn.evbuc.com%2Fimages%2F328876259%2F968804569553%2F1%2Foriginal.20220803-041427?w=800&auto=format%2Ccompress&q=75&sharp=10&rect=0%2C0%2C2160%2C1080&s=de861d8a239e58076f7fa0b7b2b0aa43)

### Initial Setup

[X] 1. [Install MetaMask](https://metamask.io/)
[X] 2. [Add Moonbase Alpha Network to MetaMask via the Button at the Top of Page](https://docs.moonbeam.network/)
[X] 3. [Get funds from the faucet](https://apps.moonbeam.network/moonbase-alpha/faucet/)
[ ] 4. [Swap a tiny bit of DEV tokens for 1 xcUNIT](https://moonbeam-swap.netlify.app/#/swap) *Please only swap for 1 xcUNIT at this time - you'll need to save your DEV for future transactions in the workshop.* 
[ ] 5. [Download and Install Polkadot JS Extension](https://polkadot.js.org/extension/)
[ ] 6. Create an Account in the Polkadot JS Extension and Select *allow use on any chain*

### Perform a Cross Chain Swap via XCM
[ ] 1. [Head to Moonbeam Apps](https://apps.moonbeam.network/moonbase-alpha/)
[ ] 2. Transfer 1 xcUNIT token to the Moonbase Relay Chain. Verify arrival by heading to [Moonbase Relay Polkadot JS](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Ffrag-moonbase-relay-rpc-ws.g.moonbase.moonbeam.network#/accounts)
[ ] 3. Transfer some of the xcUNIT token from the Moonbase Relay Chain back to Moonbase Alpha.
[ ] 4. I will make a sample XCM Transfer of DOT from Polkadot to Moonbeam. You can find the exact transaction hash and transfer details here: https://polkaholic.io/chains/#xcmtransfers. Once you have found the txn, click on extrinsic details.
[ ] 5. Using the transaction hash that you found in the prior step, look up the transaction details on [Polkadot Subscan](https://polkadot.subscan.io/)

### Send a Cross Chain Message with Axelar
[ ] 1. [Head to this blog post written by Jeremy from Moonbeam Developer Relations Team](https://moonbeam.network/blog/connected-contracts-axelar/)
[ ] 2. [Open up Remix](http://remix.ethereum.org/)
[ ] 3. [Copy SimpleGeneralMessage.sol into Remix](https://gist.github.com/jboetticher/0188244031df80e9b180568e30bfa7a5)
[ ] 4. Send a cross chain message from Moonbeam to Ethereum. Note, we are performing these steps on testnet but Axelar refers to each chain by its mainnet name.
[ ] 5. Send a cross chain message from Moonbeam to another network of your choice. Remember to change the relevant network name, destination address, and amount of WEI sent for gas. 
[ ] 6. Track the status of your cross chain message by looking up the transaction on [AxelarScan](https://testnet.axelarscan.io/)

### Extra-Curriculars (Post Workshop) 
* [Send XC-20s Cross Chain with XCM](https://docs.moonbeam.network/builders/xcm/xc20/xtokens/) 
* [Try out remote execution with XCM](https://docs.moonbeam.network/builders/xcm/xcm-transactor/)
