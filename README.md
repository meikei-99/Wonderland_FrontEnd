# Wonderland @Goerli testnet

The Web3 journey of Disney continues with the launch of its brand new NFT collection, Wonderland, on the Goerli testnet.
For NFT and Disney fans, Wonderland is an NFT marketplace where you can mint, buy, sell, and discover exclusive Disney NFT drops.
Wonderland NFT holders will be able to experience special perks and discounts at the partnered Disneyland parks.

## **Functionality**
- Mint, Approve, List: Access will be granted to whitelisted members to free mint, approve, and list the NFT on the Wonderland marketplace. There is only a minimal transaction fee to pay. Take note that everyone is considered a whitelist member during the current development phase. The listing price of the NFT must be specified at the listing stage.
- Update: The price of the listed NFT can be updated on the profile page under the section of `Your Listed NFTs`.
- Buy: Anyone who wants to become a Wonderland NFT holder can buy the NFT on the market page.

## **Things to take note**
- NFT image on the market page will not show up if Metamask account is not connected. Image of gradient background will appear instead of the actual NFT image.
- If your Metamask account was connected but you still get gradient background display as NFT on the market page, please be patient and wait for a moment. 
- Take note that the image on mint page might take time to load.

## **What if you encountered the following page loading error?**

```
ipfs resolve -r /ipfs/bafybeifocupu3e5ts4dosecxmsqbrwtkbjcenvmkkvz7dvou5vlk6jr5o4/Profile: no link named "Profile" under bafybeifocupu3e5ts4dosecxmsqbrwtkbjcenvmkkvz7dvou5vlk6jr5o4
```

For example, you are now on the profile page and wish to reload the page. You might encounter the error as stated above. When you try to press the reload button, the same error appear. <br/><br/>
How to solve this problem??<br/><br/>
You should now have this address `wonderland.on.fleek.co/Profile` on your browser's address bar. Remove the `/Profile` and reload the page. The problem might be resolved.  

## **What I learnt**
- learn to use reentrancy guard in the smart contracts to protect from reentracy attack 
- learn to use and create own function modifier
- learn to implement functions of ERC721
- learn to index data using The Graph 
- learn to upload tokenURI of ERC721 to IPFS using Pinata

## **Language/Framework/Library used**
- Solidity
- Next.js
- ether.js
- Javascript
- Tailwind 
- Three.js

### **Disclaimer**
The dapp is still in development mode and future improvement is needed. 
Thank you. 

Kindly refer to the Github repository (Wonderland_Backend) for the code of smart contract.


