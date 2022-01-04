# Stake AVAX, by Validating or Delegating, with the Avalanche Wallet通过Validating或者Delegating再钱包内质押AVAX

## **Introduction简介** <a href="#001f" id="001f"></a>

The Avalanche Wallet is a web-based application with no middleware or any kind of server communication. The Avalanche Wallet is written in Vue JS and can be either accessed online or compiled and run locally.

The Avalanche Wallet can be accessed [here](https://wallet.avax.network).\
The Avalanche Wallet source code can be found [here](https://github.com/ava-labs/avalanche-wallet).

**Let’s get staking!**

### **Step 1 — Open the Avalanche Wallet** <a href="#552d" id="552d"></a>

![Image for post](https://miro.medium.com/max/1552/0\*tpBIOjLdppuNKMjA)

You can access your wallet using your key phrase, keystore file, or Ledger Nano S (coming soon!)

### **Step 2 — Navigate to "Earn" section** <a href="#dc5a" id="dc5a"></a>

![Image for post](https://miro.medium.com/max/1504/0\*XTh3nZzBI1bkLbwO)

**To stake, you need to have your funds available on the** [**Platform Chain (P-Chain)**](../../../learn/platform-overview/#platform-chain-p-chain)**! If your funds are on the** [**Exchange Chain (X-Chain)**](../../../learn/platform-overview/#exchange-chain-x-chain)**, we will need to transfer them to the P-Chain by initiating a cross-chain transfer. If your tokens are locked they are already on the P-Chain, so you don’t need to perform the Cross Chain Transfer from X-Chain to P-Chain.**

![Image for post](https://miro.medium.com/max/1522/0\*xKAf0nXSzqIdmBDg)

Enter the amount you wish to transfer to your P-Chain and complete the transfer by clicking the "Transfer" button below.

![Image for post](https://miro.medium.com/max/1488/0\*aremeYNYtKP5nGPx)

Voila!

![Image for post](https://miro.medium.com/max/1512/0\*XP8f8CISy-LJ\_Lc3)

Now, we have our funds ready for staking on the P-Chain. Next, you can add a validator or a delegator to your wallet.

### **Step 3A: Become a validator!** <a href="#60f0" id="60f0"></a>

To add a validator, we need to have a node running. We can set one up using the released [binaries](https://github.com/ava-labs/avalanchego/releases/) or build them from the [AvalancheGo source code](https://github.com/ava-labs/avalanchego).

Using the binaries is easy and convenient and sets you up to be a validator in 4 steps:

* Download the latest release tar.gz (zip for osx and windows) found [here](https://github.com/ava-labs/avalanchego/releases)
* Unpack into a folder of our choosing:

\* Linux: tar -xvf avalanchego-linux-\<VERSION>.tar.gz

\* OSX: unzip avalanchego-macos-\<VERSION>.zip

\* Windows: unzip avalanchego-win-\<VERSION>.zip

* Navigate to the binaries directory cd avalanchego-\<VERSION>
* Run the binary with ./avalanchego on Linux and OSX and AvalancheGo on Windows

We will let our node bootstrap and sync with the rest with the network, and we are ready to roll.

We will need our Node ID. Let’s find that using the [info API](../../avalanchego-apis/info-api.md)!

If you need any help setting up your node, join us on [Discord](https://chat.avax.network).

![Image for post](https://miro.medium.com/max/1600/0\*6hZSaT651Dd7R4bL)

Fill the fields and confirm!

![Image for post](https://miro.medium.com/max/1600/0\*cy61ZMDY5veMvCZj)

Carefully check the details, and click "Confirm" again!

![Image for post](https://miro.medium.com/max/1600/0\*f3GlN03He6TFkOV7)

Congratulations. You are now validating the Avalanche Primary Network!

### **Step 3B: Add a Delegator!** <a href="#59bd" id="59bd"></a>

![Image for post](https://miro.medium.com/max/1600/0\*f-wXi2SiSm4eBmHt)

Select a validator you want to delegate your tokens with from the list of active network validators.

![Image for post](https://miro.medium.com/max/1600/0\*uNnT2PtjCslRKFbF)

Specify your staking period and stake amount. Pay attention to the end time of the selected validator. Your delegation period cannot be set to end past the end date that the validator has set.

![Image for post](https://miro.medium.com/max/1600/0\*M\_6\_7L9jtYuPTp-A)

Confirm the details!

![Image for post](https://miro.medium.com/max/1600/0\*Silj8-uZTm5g9xSi)

Congratulations. You are now delegating the Avalanche Primary Network!
