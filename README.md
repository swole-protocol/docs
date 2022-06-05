# Swole-Protocol 💪

After a long time sitting down and being inactive during the long grind of a hackathon, the best thing we can do shake out the cobwebs is to get up, move around and get swole! That's where swole-protocol is here to help!

## What
Swole-Protocol aims to be the go-to decentralized source of truth for exercise data and will provide personal trainers (and anyone really) to create customized workouts as NFT's which they can perpetually profit from secondary market sales.  Swole-Protocol is fitness but with a web3 twist 💪

## Why

Fitness and health are often overlooked by folks in the tech space but especially those exploring web3 as we tend to get lost in the Infinite rabbit hole.  We need to remember to get up and move around once in a while!  What's more is that personal trainers and fitness celebrities typically gain popularity by posting their "special" workout regimens but are often at the mercy of a social media platform using their content to pump their bags.  We've seen creators and artists start to claim the profits that their Intellectual property deserves and now it's time for the personal trainers and homemade bodybuilders to do the same.

On the other-side of the coin, their does currently exist a open source project that houses exercise data contributed by the community; however, this data is held in a centralized server and is susceptible to one day being taken down (as we've seen often with some open-source projects).  Exercise has been around for centuries and it's time to build its "Alexandria Library" using the building blocks that web3 provides.

## How 

- All exercises are stored on the Arweave storage protocol as the nature of an exercise as exercises don't often change so very appropriate for permenant storage so 
- Minting of the workout is done via a smart contract deployed on Polygon mainnet
- NFT data is stored in a permenant way on IPFS (via Pinata)
- Subgraph deployed to mainnet to index the workouts that are minted.  This subgraph is then queried on the 'workouts' page to display (at the moment) all the workouts minted on-chain.

# Bounties

- **Polygon** -> Deployed NFT smart contract to Polugon mainnet
- **Graph** -> created subgraph to index minted workouts (deployed to mainnet)
- **IPFS/Filecoin** -> Using IPFS (via Pinata) to store the workout metadata for the NFT
- **Coinbase Inc** -> Using RainbowKit we added the ability for the user to sign in with their coinbase wallet to be able to mint their workout
