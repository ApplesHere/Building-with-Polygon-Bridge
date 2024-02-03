# Building-with-Polygon-Bridge


1. **Generate a 5-item collection using DALLE 2 or Midjourney:**
   - Use DALLE 2 or Midjourney to generate a collection of 5 unique items.

2. **Store items on IPFS using pinata.cloud:**
   - Upload the generated items to IPFS using pinata.cloud or any other IPFS service.

3. **Deploy an ERC721 or ERC1155 to the Goerli Ethereum Testnet:**
   - Deploy a smart contract on the Goerli Ethereum Testnet that complies with the ERC721 or ERC1155 standard.

4. **Prompt Description function:**
   - Implement a function in the smart contract named `promptDescription` that returns the prompt used to generate the images.

5. **Map Your NFT Collection using Polygon network token mapper:**
   - Optionally, map your NFT collection using the Polygon network token mapper for visualization purposes.

6. **Write a Hardhat script to batch mint all NFTs:**
   - Develop a Hardhat script that allows for batch minting of all NFTs. Utilize ERC721A standards for optimal efficiency.

7. **Write a Hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge:**
   - Create a Hardhat script that facilitates batch transfer of all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge.

8. **Approve the NFTs to be transferred:**
   - Implement a function in the smart contract to approve the transfer of NFTs from Ethereum to Polygon Mumbai.

9. **Deposit the NFTs to the Bridge:**
   - Write a function to deposit the NFTs to the FxPortal Bridge for transfer to Polygon Mumbai.

10. **Test balanceOf on Mumbai:**
    - Perform tests to ensure that the `balanceOf` function works correctly on the Polygon Mumbai network after the NFTs have been transferred.
