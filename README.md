# Joint Savings Smart Contract

This repo contains a Solidity smart contract that implements a joint savings account.

The smart contract allows for creation of an account that uses two user addresses.  It uses ether management functions to provide the features of the joint savings account, which include getting information about the account, as well as the ability to deposit and withdraw funds.

---

## Technologies

Solidity: The smart contract is written in Solidity and compatible with Ethereum-based blockchains.

---

## Installation Guide

This smart contract can be compiled and deployed, and tested using the JavaScript VM in the Ethereum Remix IDE.

See the **Examples** section below for results of testing the contract in this way.  

---

## Examples

### Testing, Step 1

Result of using the `setAccounts` function to set two user addresses for the joint account:

![1_setAccounts](Execution_Results/1_setAccounts.png)

### Testing, Step 2

Result of depositing 1 ether as wei:

![2_1_1_deposit_1_ether_as_wei](Execution_Results/2_1_1_deposit_1_ether_as_wei.png)

Checking the contract balance after depositing 1 ether as wei:

![2_1_2_contractBalance_1_ether](Execution_Results/2_1_2_contractBalance_1_ether.png)

Result of depositing 10 ether as wei:

![2_2_1_deposit_10_ether_as_wei](Execution_Results/2_2_1_deposit_10_ether_as_wei.png)

Checking the contract balance after depositing 10 ether as wei:

![2_2_2_contractBalance_11_ether](Execution_Results/2_2_2_contractBalance_11_ether.png)

Result of depositing 5 ether:

![2_3_1_deposit_5_ether](Execution_Results/2_3_1_deposit_5_ether.png)

Checking the contract balance after depositing 5 ether:

![2_3_2_contractBalance_16_ether](Execution_Results/2_3_2_contractBalance_16_ether.png)

### Testing, Step 3

Result of withdrawing 5 ether to account 1:

![3_1_1_withdraw_5_ether_into_accountOne](Execution_Results/3_1_1_withdraw_5_ether_into_accountOne.png)

Checking the contract balance after withdraw to account 1:

![3_1_2_contractBalance_after_withdraw_to_accountOne](Execution_Results/3_1_2_contractBalance_after_withdraw_to_accountOne.png)

Checking the last address to withdraw after withdraw to account 1:

![3_1_3_lastToWithdraw_after_withdraw_to_accountOne](Execution_Results/3_1_3_lastToWithdraw_after_withdraw_to_accountOne.png)

Checking the last withdraw amount after withdraw to account 1:

![3_1_4_lastWithdrawAmount_after_withdraw_to_accountOne](Execution_Results/3_1_4_lastWithdrawAmount_after_withdraw_to_accountOne.png)

Result of withdrawing 10 ether to account 2:

![3_2_1_withdraw_10_ether_into_accountTwo](Execution_Results/3_2_1_withdraw_10_ether_into_accountTwo.png)

Checking the contract balance after withdraw to account 2:

![3_2_2_contractBalance_after_withdraw_to_accountTwo](Execution_Results/3_2_2_contractBalance_after_withdraw_to_accountTwo.png)

Checking the last address to withdraw after withdraw to account 2:

![3_2_3_lastToWithdraw_after_withdraw_to_accountTwo](Execution_Results/3_2_3_lastToWithdraw_after_withdraw_to_accountTwo.png)

Checking the last withdraw amount after withdraw to account 2:

![3_2_4_lastWithdrawAmount_after_withdraw_to_accountTwo](Execution_Results/3_2_4_lastWithdrawAmount_after_withdraw_to_accountTwo.png)

---

## Contributors

Michael Danenberg

---

## License

MIT