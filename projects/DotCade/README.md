
<img width="1624" alt="Screenshot 2024-11-29 at 18 31 25" src="https://github.com/user-attachments/assets/912fcc59-8785-4751-8197-72ef95d80bd7">

  

# DotCade

  

### DotCade

**Team Members**:

- Prathamesh Mutkure 
  - [GitHub](https://github.com/prathamesh-mutkure)
  - [LinkedIn](https://linkedin.com/in/prathamesh-mutkure)
  - [X](https://x.com/prathamesh_io)

  

---

  

## Demo & Links

  

-  **Live Demo**: [Insert link here]

-  **GitHub Repository**: https://github.com/prathamesh-mutkure/dotcade-polkadot

-  **Video Demo**: [Insert link here]

  

---

  

## Project Overview

  

**Description**:

DotCade is an gaming marketplace and launchpad with a unified gaming identity powered by TrueNetwork shared across game so that developers don't need to worry about finding new users.

DotCade also provides SDKs for web2 developers to build and launch their apps without worrying about the on-chain complexities.
  

**Key Features**:

- Support for Adobe Flash games
- Social auth
- SDK for developers
- Gaming identity shared across games

**Technology Stack**:

-  **Blockchain/Parachains**: TrueNetwork, MoonBeam

-  **Frontend**: Next.js

-  **Centralised Component (if any)**: NA

-  **Other Useful Tools**: Ruffle Emulator, MagicLink Wallet

  

---

  

## Progress & Changelog

  
  

### Day 1 (27/11/2024):

- Achievements:
  - Researched Polkadot and Parachains
  - Finalised the idea after discussion with mentors
  - Finalised tech stack

- Challenges:
  - Pivoted the idea at end of the day
  - Accessing technical feasibility of the project  

  

### Day 2 (28/11/2024):

- Achievements:
  - Initialised the project
  - Integrated Adobe Flash games
  - Tested a few games
  - Designed user flows 

- Challenges:
  - Getting Adobe flash games running
  - Ruffle giving state and DOM issues

  

### Day 3 (29/11/2024):

- Achievements:
  - Finalised the UI/UX
  - Setup True Network
  - Fixed DOM and state issues with Ruffle

- Challenges:
  - Challenges with reputation-cli


### Day 4 (30/11/2024):

- Achievements:
  - Integrated True Network
  - Attested on-chain data
  - Added more games
  - User Profile page
  - Started work on Smart Contracts

- Challenges:
  - New datatypes in True SDK
  - Working with Ink


---


  

## How to Run Locally

  

### Prerequisites

- Node.js 22
- PolkadotJS wallet
- `reputation-cli` installed and setup
  

### Steps

```bash

# Clone the repository

git  clone  https://github.com/dotcade-polkadot.git

cd frontend


# Install dependencies

pnpm install


# Setup .env

TRUE_NETWORK_SECRET_KEY=<your-true-network-secret>
  

# Start the application

pnpm  run dev