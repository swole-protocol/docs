# Swole-Protocol 💪

## Introduction
After long periods of being inactive during a day at the office or the long grind of a hackathon, the best thing to do is to get up, move around and get swole! That's where swole-protocol is here to help!

Our platform enables a fully decentralized personal training marketplace that allows anyone to connect anywhere and get fit! We provide a credibility standard for all personal trainers (PT) so you can be sure the workout you're getting is the highest quality.

## Problem
* PTs (Personal Trainers) lose 40-60% to "Big Gym"
* Credibility of "entertainer" workouts on social media may not be trustworthy

## Solution
* Enable distributed PT market
* Integrate Web3 Profile Points to establish Credibility

## Key Aspects
* Anyone can offer a workout (aka "Trainer")
* Anyone can join a workout (aka "Trainee")
* Swole Protocol is a stand-alone software "tool"
* Swole Protocol DAO will facilitate the functionality/governance of the community.
* Swole Protocol DAO will act as an umbrella that provides funding to build out key features (ie. Swole Protocol software, DeGyms, Specialized workout equipment, etc.)

## How
* Anyone can create a workout that is minted on chain as a partially mutable NFT.
* Each workout is minted as a single nft and we do not prevent duplicates
* The NFT has some key characteristics:
  * NFT has mutable information such as level, # of times used, likes, dislikes, etc.
  * The nft level is calculated by a combination of all other information.
  * The level can go up or down based on the most updated information
  * Anyone can view the workout and perform the exercises at any time
  * Only the owner of the nft is able to issue credit/rewards for completing the workout

* For the trainee, there are two actions for interacting with the nft, "demo workout" and "record workout".
  * "Demo Workout" is a free service that all nft workouts have by default. Non-transaction service
    * No rewards can be issued in this mode
    * At a minimum this allows trainees to step through the minted exercises
    * Beyond the minimum, the trainer can choose what else to include in the demo version (live videos, irl meetups, etc)

  * "Record Demo" transaction service
    * In this mode rewards are distributed, nft mutable information can be updated
    * The price of this service is set by supply-demand market of the Trainor and trainee.
    * The cost to mint mutable information and a governance tax is paid by the trainee
    * The amount of distributable rewards is proportional to the nft level. Higher the level, the more rewards can be distributed.
    * The trainer is able to cover the cost of this service for "x" trainees for promotional events.

## Motivations
**Trainer:**
  * Create NFT: The value of the nft is expected to increase proportional the level of the nft. A high level means that more rewards can be issued to trainees and thus attracting more trainees. The Motivation to create can either be to sell or to own.
  * Own an NFT: Additional to the value increase mentioned above, the nft generates revenue. Every trainee that chooses to record a workout is paying that trainer for the service. It's in the trainer's best interest to offer the best training (virtual, irl, live, recorded, one-on-one, etc) service possible to keep clients coming back and keep generating revenue. The quality of graphics, content and workout explanations should be driven by this mechanism.

NOTES: initial NFT is required for trainors/trainees before transaction services are enabled - Raise funds for the DAO

**Trainee:**
* The trainees motivation is to get fit. They receive non-transferable rewards that don't have monetary value but are used to level up a web3 profile. This is used to build credibility if they decide to also create/hold nft workouts. Trainees are responsible for signaling good/bad workouts. Good workouts move up the ladder while bad ones remain stagnant or drop.
  
NOTES: Utilize fitness phone/watch data in trainee's profile level
  
**Profiles:**
* Anyone with a profile can subscribe to other profiles to receive latest workout releases.
* Profiles can receive staking.

**Staking: (still be finalized)**
* Anyone can stake to a profie. A profile that receives stake, can choose to distribute some portion of revenue to stakers.
* Stake can be used to "borrow" nft workouts from other trainers. Ie. I want to borrow a high level workout that I plan to demonstrate at an event but can't afford to buy it - what happens to mutable information in this case? Stake cannot leave the platform due to potential liquidity issues.

## Summary
The mechanisms described above are really all part of a tool yet to be developed (swole protocol). They're may be a need for a token. The DAO is an umbrella organization that may or may not be needed in the future. Our focus is to develop the mechanism. The DAO is not a priority atm.

## Roadmap:

**1. Fundraise**
* Need dev resources
* Possibly issue equity (in tokens?)
* May need to incorporate
  * DAOs incorporate out of Caymans non-profit (50K usd for setup)
  * Swole Protocol incorporate as LLC - Possibly in the states
* Create a pitch deck for funding applications
* We should come up w/ a funding goal that would be able to take us through mvp.
* Post project on Gitcoin to gauge dev interest

**2. Develop a mvp that demonstrates all the functionality.**
* Web 3 profiles
* Mint Exercises
* Partially mutable nfts
* Two actions on nft

**3.  User feedback along the way**
* Try out features as we go
* Our short term goal would be a small sampling size of 5 users.
* This is when we start building community on social platforms.

## Why

Fitness and health are often overlooked by folks in the tech space but especially those exploring web3 as we tend to get lost in the Infinite rabbit hole.  We need to remember to get up and move around once in a while!  What's more is that personal trainers and fitness celebrities typically gain popularity by posting their "special" workout regimens but are often at the mercy of a social media platform using their content to pump their bags.  We've seen creators and artists start to claim the profits that their Intellectual property deserves and now it's time for the personal trainers and homemade bodybuilders to do the same.

On the other-side of the coin, their does currently exist a open source project that houses exercise data contributed by the community; however, this data is held in a centralized server and is susceptible to one day being taken down (as we've seen often with some open-source projects).  Exercise has been around for centuries and it's time to build its "Alexandria Library" using the building blocks that web3 provides.

## Technical Implementation

## How 

- All exercises are stored on the Arweave storage protocol as the nature of an exercise as exercises don't often change so very appropriate for permenant storage so 
- Minting of the workout is done via a smart contract deployed on Polygon mainnet
- NFT data is stored in a permenant way on IPFS (via Pinata)
- Subgraph deployed to mainnet to index the workouts that are minted.  This subgraph is then queried on the 'workouts' page to display (at the moment) all the workouts minted on-chain.

# Bounties

- **Polygon** -> Deployed NFT smart contract to Polugon mainnet
- **Graph** -> created subgraph to index minted workouts (deployed to mainnet)
- **IPFS/Filecoin** -> Using IPFS (via Pinata) to store the workout metadata for the NFT and deployed the application to IPFS using Spheron 
- **Coinbase Inc** -> Using web3modal we added the ability for the user to sign in with their coinbase wallet to be able to mint their workout
