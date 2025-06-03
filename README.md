# Smart-Contract-Lottery

A raffle contract that utilizes Chainlink VRF and Automation to pick up a random winner after enough time has passed. For some reason, automation isn't working but we'll figure out why soon.

Contract deployed at: 0xFdcCcace215a3E8E92EB7FAFBB1c361070e5cfaA

Set up an account
```bash
cast wallet import myaccount --interactive
```

Call script to fund subscription
```bash
forge script script/Interactions.s.sol:FundSubscription --rpc-url $SEPOLIA_RPC_URL --account myaccount --broadcast
```

Use makefile commands for installation, deployment, etc. 