Notes: 

1. Solana has programs. They are what we call "smart contracts" in Ethereum. .
2. The RPC nodes provided by companies like Alchemy, QuickNode, etc. are RPC servers to communicate to the blockchain.
3. JSON RPC is the communication protocol of blockchain.


Solana CLI: 

1. Installation on Mac/Linux: `sh -c "$(curl -sSfL https://release.solana.com/v1.18.18/install)"`

Create a new cli wallet: `solana-keygen new`
Set the RPC url: `solana config set --url https://api.devnet.solana.com`
Airdrop yourself some SOL: ` solana airdrop 1`
Check your balance: `solana balance`
Create token mint: `spl-token create-token`
Verify token mint on chain: By going to "https://explorer.solana.com/address/<token address>"
Check the supply of the token: `spl-token supply AQoKYV7tYpTrFZN6P5oUufbQKAUr9mNYGe1TTJC9wajM`
Create an associated token account: `spl-token create-account ChNkv9iW5pZJ1YAsNswC2CrdMUkFJBUbRWinjdLvKpXA`
Mint some tokens to yourself: `spl-token mint  ChNkv9iW5pZJ1YAsNswC2CrdMUkFJBUbRWinjdLvKpXA 100`
 
Check your balances in the explorer: By going to "https://explorer.solana.com/address/<token address>"
Import the token in Phantom and see the balances.
