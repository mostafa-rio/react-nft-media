## **React NFT Slider**

A React component that creates a slider showcasing NFTs from a specific collection without the need for connecting a wallet or using Web3.js or Ether.js.

## **Features**

*   Fetches NFTs from a collection using the collection address
*   Displays NFTs in a responsive and interactive slider
*   Supports touch and mouse drag gestures for easy navigation
*   Customizable styling and appearance
*   Lightweight and easy to integrate into your React projects

## **Installation**

npm

```plaintext
npm install react-nft-slider

```

yarn

```plaintext
yarn add react-nft-slider

```

## **Usage**

```plaintext
import React from 'react';
import NFTSlider from 'react-nft-slider';

const MyNftSlider = () => {
  const collectionAddress = '0x...'; // Replace with your desired collection address

  return (
    <div>
      <h1>My NFT Collection</h1>
      <NFTSlider collection={collectionAddress} />
    </div>
  );
};

export default MyNftSlider; 
```

## **Props**

*   **collection** (required): The address of the NFT collection to fetch NFTs from.

## **License**

This project is licensed under the [MIT License](https://chat.openai.com/link-to-license).