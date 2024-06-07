zeekMessage Contract: https://sepolia.explorer.zksync.io/tx/0x2a6de29d7edc1e8dd162bbe250524cb3bb58ac8937715d5dcf7998437901dba1

ERC20 Token Contract: https://sepolia.explorer.zksync.io/tx/0x555dbaf47f72173583629977d9aca9ce4645c65556354994eaacfdf8e988038c#overview

My zkSync Progress__
First, I set up all prerequisites, then I started with the zeekMessage example. Deployed it and made some transactions to make sure it runs well.

Then, I deployed ERC20 Token Contract. I tested the contract, mint some tokens via mint-token.ts file and transfer the tokens to my another wallet by using interact section in Remix.

Lastly, I used paymaster-transaction.ts file to use paymasters contract. It allowed me to use the ERC20 tokens for fees.

I learned how to write smart contracts in zkSync and what is a paymaster.
