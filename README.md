# Debugging-Smart-Contract
Debugging a smart contract by Truffle - http://truffleframework.com/tutorials/debugging-a-smart-contract

At Step 7) migrate, I encountered error

**------------------------------------------**

truffle(develop)> migrate
Using network 'develop'.

Running migration: 1_initial_migration.js
  Deploying Migrations...
  ... 0x29a4df52b32af807c1f91148d1422cfaae8f2711bbaea69aa50da29da377e8e1
  Migrations: 0x8cdaf0cd259887258bc13a92c0a6da92698644c0
Saving successful migration to network...
  ... 0xd7bc86d31bee32fa3988f1c1eabce403a1b5d570340a3a9cdba53a472ee8c956
Saving artifacts...
Running migration: 2_deploy_contracts.js
/simple-storage/migrations/2_deploy_contracts.js:3
module exports = function(deployer) {
       ^^^^^^^

SyntaxError: Unexpected identifier


**------------------------------------------**

