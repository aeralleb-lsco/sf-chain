# sf-chain
Node based Blockchain with apis and peer-peer network


![image](https://user-images.githubusercontent.com/87722127/174416288-399e8d50-d8bd-43eb-97c6-7e9b5c5f3dbf.png)

![image](https://user-images.githubusercontent.com/87722127/174416309-88afadfb-12a5-4402-889d-0230741fbe41.png)

![image](https://user-images.githubusercontent.com/87722127/174416319-637f2b1c-5321-4d15-9392-716a431a06fd.png)

Ideas on Extending the Project
You may still have the itch to extend this blockchain-based cryptocurrency. Here are some ideas for features that you could add:

A GET ‘/balance’ endpoint that allows the user to calculate their balance based on the blockchain, and view it at any time.

Add transaction fees for each user, of 1 currency. Include these fees as part of the reward for the miner.

Develop a frontend, where a user can see every fellow user’s public addresses, and send currency to the individual. This frontend could show the current difficulty of the system. It could have buttons for mining the transactions, or viewing the blockchain data. Use your imagination.

An implementation where the Miner’s mine() function only grabs a group of the transactions, and not the entire pool. When the subset of transactions from the pool is included in the chain, they would need to be cleared from the pool, and synchronized across all miners.

Route the blockchain-approved reward transactions through its own dedicated server. That way, not everyone can create transactions through the special blockchain wallet.

Let me know if you decide to implement any of these, and have some working code. I would love to see it.
