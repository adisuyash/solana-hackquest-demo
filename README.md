# Deploying Your First Smart Contract on Solana Devnet

In this guide lesson, you will learn how to deploy and interact your Bulls and Cows game (a number guessing game) using the Solana Playground.

## Prerequisites

Before starting, make sure you have:
- A [Solana Playground](https://beta.solpg.io/) account.
- Basic knowledge of Solana smart contracts and Rust programming.

## Steps to Complete the Lesson

### 1. Create a New Solana Project
1. Open Solana Playground.

2. Click on the `+` in the **EXPLORER** on the left to create a new Solana project:
   - **Project Title**: Enter your desired project name.
   - **Template**: Select `Anchor(Rust)`.
---


### 2. Add Smart Contract to `lib.rs`
1. In the **EXPLORER** panel, navigate to `src/lib.rs`.

2. Replace the existing content with the code in this file [`BullsAndCows.rs`](https://github.com/adisuyash/solana-hackquest-demo/blob/main/BullsAndCows.rs).
---


### 3. Add Client Interaction Code to `client.ts`
1. Navigate to client/client.ts.

2. Replace the existing content with the code in this file [`Client.ts`](https://github.com/adisuyash/solana-hackquest-demo/blob/main/Client.ts).
---


### 4. Build & Deploy

1. Switch to the Build & Deploy tab on the left side of Solana Playground.

2. Create a Solana Wallet by clicking on the `Connect to Playground Wallet`:
   - Save the keypair.
   - Hit Continue. Your Solana Wallet have been created!

3. Now visit [Solana Devnet Faucet](https://faucet.solana.com/) and enter your newly created Solana Wallet address to get devnet tokens.

4. Click on Build.

5. After a successful build, click the Deploy button.
---

### 5. Initialize the Program
1. In `client/client.ts`, click the Run button under Client to initialize the program and generate a random number.
---


### 6. Start the Game
1. Comment out the initialization code in `client/client.ts` by changing `initialize();` to `//initialize();`.

2. Uncomment the guessing code `// guessing(0);` and replace 0 with your guessed number.

3. Click Run under Client to see if your guess was correct.
---


🎉 Congratulations! You have successfully deployed your first Smart Contract on Solana Devnet.

For any issues or further assistance, feel free to reach out to [AdiSuyash](https://x.com/adisuyash).
