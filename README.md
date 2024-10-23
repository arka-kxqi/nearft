
# NEARFT

## Inspiration
NEARFT originated from my earlier project where users could create unique CSS gradient patterns dynamically. I envisioned this design capability being transformed into NFTs, allowing users to not only express their creativity but also to monetize their designs.

## What It Does
NEARFT enables users to create and customize their own design patterns and sell them as NFTs. This project combines creative expression with blockchain technology, allowing artists and designers to showcase and sell their work.

## How We Built It
The development process began with selecting the overall design of the product, followed by a step-by-step build approach. Key technologies used include:

- **Hardhat** for blockchain development
- **Next.js** for the front-end
- **Solidity** for smart contracts
- **Tailwind CSS** for styling
- **TypeScript** for type safety

## Challenges We Ran Into
1. **Wallet Integration:** Choosing the best wallet connector library proved challenging. After testing various options (Rainbow Kit, wagmi.sh, and web3Onboard), I settled on web3Onboard.
  
2. **Design Pattern Tool Issues:** Developing a dynamic gradient design tool resulted in several challenges, such as color mismatches and difficulties in generating the design patterns.

3. **Minting NFTs:** Converting CSS designs into images for minting posed technical issues, particularly with file generation and IPFS storage. These were resolved through extensive research and community assistance on StackOverflow.

4. **TypeScript Compatibility:** Encountering issues with type mismatches in TypeScript, especially when using React hooks like `useRef`, necessitated careful debugging.

5. **Blockchain Data Integration:** Challenges arose in fetching data from the blockchain and handling the BigNumber format, requiring conversion to standard numeric types.

## Accomplishments That We're Proud Of
- Successfully built a user-friendly design interface.
- Learned how to expedite project completion by setting clear goals and implementing them effectively.

## What We Learned
This project has taught me the importance of user-friendly design and the value of clear goal setting. I gained hands-on experience in developing a comprehensive NFT application, deepening my understanding of both front-end and blockchain technologies.

## What's Next for NEARFT
Plans include adding an NFT collection feature and expanding the design pattern options to enhance user engagement.

## Built With
- Hardhat
- Next.js
- Solidity
- Tailwind CSS
- TypeScript

## Try It Out
Visit the live project: [NEARFT](https://color-brand-fronted-react.vercel.app/)