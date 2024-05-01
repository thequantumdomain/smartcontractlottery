# Proveable Random Raffle Contracts

## About

This code is to create a proveable random smart contract lottery.

## What do we want it do?

1. User can enter by paying for a ticket.
2. Ticket fees will go to the winner during the draw
3. After X period of time, the lottery will automatically draw a winner.
4. This will be done programatically
5. Using Chainlink VRF and Chainlink Automation
   1. Chainlink VRF -> Generate proveably random number 
      1. (true randomness on-chain difficult due to determinism)
   2. Chainlink Automation -> Time-based trigger for our lottery to automatically trigger
      1. (for something to happen on-chain, someone has to trigger something/gas has to be paid; if we have to rely on that, automation by chainlink is more decentralised, trustless.)
   
## Tests

1. Write deploy scripts
2. Write tests 
   1. Local chain
   2. Forked testnet
   3. Forked mainnet# smartcontractlottery
