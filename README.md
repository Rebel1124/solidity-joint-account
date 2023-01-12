# solidity-joint-account

## Background

<br>

For this module challenge, we will be using smart contracts to automate the creation of savings accounts. The smart contract we create will accept two user addresses with both of them being able to control the joint savings account.

<br>

## Deplot and Assign User Accounts

<br>

After creating and compiling our joint_savings.sol smart contract we are then able to deploy the contract in the remix test environment (JavaScript VM).

The first step after deploying would be to assign addresses to the two accounts. This can be seen in the first screenshot below.

<br>

![Set Accounts](Execution_Results/setAccounts.png)

<br>

## Transaction 1 - Send 1 ether as wei
<br>
For the first transaction, we send 1 ether (as wei) from one of the dummy wallets in the test environment (JavaScript VM). The screenshot below shows the wallet we are sending the ether from.

<br>

![Transaction1 - send 1 eth](Execution_Results/transaction1_send_1wei.png)

<br>

The screenshot show that the ether has indeed gone to our smart contract, with the account balance now at 1 ether.

<br>

![Transaction1 - account balance](Execution_Results/transaction1_accountBalance.png)

<br>

## Transaction 2 - Send 10 ether as wei
<br>
For the second transaction, we send 10 ether (as wei) from one of the dummy wallets in the test environment (JavaScript VM). The screenshot below shows the wallet we are sending the ether from.

<br>

![Transaction2 - send 10 eth](Execution_Results/transaction2_send_10wei.png)

<br>

The screenshot show that the ether has indeed gone to our smart contract, with the account balance now at 11 ether.

<br>

![Transaction2 - account balance](Execution_Results/transaction2_accountBalance.png)

<br>

## Transaction 3 - Send 5 ether
<br>
For the third transaction, we send 5 ether from one of the dummy wallets in the test environment (JavaScript VM). The screenshot below shows the wallet we are sending the ether from.

<br>

![Transaction3 - send 5 eth](Execution_Results/transaction3_send_5ether.png)

<br>

The screenshot show that the ether has indeed gone to our smart contract, with the account balanc now at 16 ether.

<br>

![Transaction3 - account balance](Execution_Results/transaction3_accountBalance.png)

<br>

## Send 5 Ether to Account 1
<br>
To test the withdrawal of funds we will send 5 ether to the account 1. We can see from the screenshot below that the smart contract accounts's balance drops to 11 ether, with the amount withdrawn at 5 ether and the last to withdraw being account 1.

<br>

![Account 1 - withdraw 5 ether](Execution_Results/withdraw_5ether_Account1.png)

<br>

## Send 10 Ether to Account 2
<br>
To test the withdrawal of funds again we will send 10 ether to the account 2. We can see from the screenshot below that the smart contract accounts's balance drops to 1 ether, with the amount withdrawn at 10 ether and the last to withdraw being account 2.

<br>

![Account 2 - withdraw 10 ether](Execution_Results/withdraw_10ether_Account2.png)