# Smart-Contract-Lottery

Set up an account
```bash
cast wallet import myaccount --interactive
```

Call script to fund subscription
```bash
forge script script/Interactions.s.sol:FundSubscription --rpc-url $SEPOLIA_RPC_URL --account myaccount --broadcast
```